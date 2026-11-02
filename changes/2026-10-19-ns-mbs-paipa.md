# NS-MBS List: PAIPA designations

- **Date:** 10/19/2026
- **Source:** OFAC recent action - https://ofac.treasury.gov/recent-actions/20261019
- **Change type:** additions (Non-SDN Menu-Based Sanctions List)

## What changed

OFAC designated entities under the Protecting American Intellectual Property
Act of 2022 (PAIPA), adding them to the NS-MBS List, and issued two associated
general licenses (including a wind-down license for entities blocked on
10/19/2026).

## Screening-relevant detail

- BEIJING QIJI CHUANGTAN PHASE I VENTURE CAPITAL CENTER LIMITED PARTNERSHIP
  carries a Chinese Simplified native name (北京奇绩创坛一期创业投资中心 有限合伙)
  and an English trading alias (a.k.a. MIRACLE PLUS RMB FUND I). A matcher that
  cannot reconcile the native-script, transliterated, and trading-name forms of
  one party will miss it in at least one script.
- Menu-based sanctions attach different prohibitions per authority (blocking,
  loan caps, FX, banking transactions, investment bans). Matching is only half
  the test; the other half is applying the correct restriction set per hit -
  NS-MBS hits are not all full blocks.

Derived fixtures are in `tests/regression-cases.json` (ids WLD-2026-10-19-001 and 002).
