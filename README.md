# watchlist-diff

A dated log of changes to public sanctions watchlists - starting with OFAC's
SDN and Non-SDN lists - with each change converted into regression fixtures for
name-matching and screening systems.

> **Status: starter draft.** Fixtures and two hand-written change entries only.
> There is no diff implementation, no test harness, and no monitoring yet. The
> update model below is the plan, to start only once the owner turns it on.

## What this is

- A changelog built from OFAC's primary records: recent-action notices and the
  official archive of list changes.
- Machine-readable fixtures derived from real changes: new aliases,
  transliteration variants, and native-script forms.

## What this is not

- Not a mirror or redistribution of watchlist data. Only the specific records
  needed for fixtures are quoted, from primary US government sources.
- Not an executable test suite. `tests/regression-cases.json` is a fixture file
  a future harness would consume; no harness exists in this starter.
- Not a screening tool, and not legal or compliance advice. A name match is a
  prompt for analyst review, never a legal determination on its own.

## Why

Two distinct risks, kept separate on purpose:

- **Additions raise missed-match risk.** New entries arrive with aliases,
  transliterations, and native-script forms. A matcher that only handles the
  primary name may fail to resolve the party at all.
- **Removals raise stale-block risk.** After a delisting, screening that still
  treats the party as listed produces stale hits.

These are different assertions. `entity match` asks whether a query resolves to
the same real-world party. `list membership` asks whether that party is on a
specific list as of a specific date. A delisted party still resolves to the
same identity - and may remain designated under other programs or lists - so a
delisting fixture asserts only "not on list X as of date Y", never that the
party is universally clear.

## Planned update model

OFAC updates on no fixed timetable. Once activated, the sources below would be
checked daily, with entries added when real list changes occur. No changes, no
commits.

## Sources (primary only)

- OFAC recent actions - https://ofac.treasury.gov/recent-actions
- Archive of changes to OFAC's sanctions lists - https://ofac.treasury.gov/specially-designated-nationals-list-sdn-list/archive-of-changes-to-the-sdn-list

Third-party aggregators (e.g. OpenSanctions) are intentionally not ingested:
their bulk data carries license restrictions, and their re-export cadence is
not the same as source-change cadence.

## Layout

- `changes/YYYY-MM-DD-<list>-<slug>.md` - what changed, per action, linked to
  the primary notice.
- `tests/regression-cases.json` - fixtures derived from the changes. Each
  case: a query, an expected party or expected list-membership state, and why.

## Known limitations of this starter

- OFAC's web notices do not print the SDN/NS-MBS unique record IDs, so fixtures
  are keyed to the primary name exactly as quoted in the notice. Anchoring each
  case to OFAC's stable record identifiers (from the SDN data files) is a
  planned follow-up before any harness runs these for real.
- Queries taken from listed aliases are exact-alias lookups: they test whether
  the matcher covers that alias string. They do not by themselves prove
  cross-script or fuzzy matching. Synthetic query variants, when included, are
  labeled `synthetic` and carry no expected-result oracle.
