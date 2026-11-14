# 2026-11-13 - SDN: Counter Narcotics and Counter Terrorism Designations

- **Source:** OFAC Recent Actions - https://ofac.treasury.gov/recent-actions/20261113
- **Release date:** 11/13/2026

## Additions

- **LOS LORENZANAS** (a.k.a. LORENZANA DRUG TRAFFICKING ORGANIZATION; a.k.a. "THE LORENZANA CLAN"; a.k.a. "THE LORENZANA FAMILY"), Guatemala; designated as a Transnational Terrorist Group, [FTO][SDGT].
- **LOS MENDOZA DRUG TRAFFICKING ORGANIZATION**, Guatemala; Honduras; Belize; [SDGT][ILLICIT-DRUGS-EO14059], linked to SINALOA CARTEL.

## Removals

None in this notice.

## Changes to existing entries

- **LOS HUISTAS DRUG TRAFFICKING ORGANIZATION** (Guatemala): the entry was republished without the alias "LOS HUISTAS DTO", and with a secondary-sanctions-risk statement, the [SDGT] program tag, and added linkages (SINALOA CARTEL; CARTEL DE JALISCO NUEVA GENERACION). The party remains designated; this is an entry change, not an addition or removal.

## Matching notes

- Alias supersession: screening keyed to the alias string "LOS HUISTAS DTO" now matches a string no longer on the entry. Historical queries using it resolve to the same listed party.
- A continued-listing assertion is included so a harness does not read an entry change as a delisting.
- The LOS LORENZANAS entry arrives with four published names (primary plus three aliases), including a descriptive "DRUG TRAFFICKING ORGANIZATION" form; matchers that only carry the primary name would miss the alias forms.

## Fixtures

Six cases, `WLD-2026-11-13-001` to `-006` in `tests/regression-cases.json`. Keyed to names as quoted in the notice; OFAC record IDs are not printed in web notices (see README, known limitations).
