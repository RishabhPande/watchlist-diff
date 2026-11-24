# 2026-11-23 - SDN: Iran-related Designations

- **Source:** OFAC Recent Actions - https://ofac.treasury.gov/recent-actions/20261123
- **Release date:** 11/23/2026
- Press release title on the notice: "Operation Economic Outcast Disrupts Iran's Global Shadow Banking Networks."

## Additions

Eight individuals, all [IRAN-EO13902], each with an Arabic-script form. Three clusters by the "Linked To" field:

- MELLAT EXCHANGE COMPANY: ABBASI, Mohammad Hossein; AKHLAGHI, Mahmoud; FAZLJU, Parviz.
- MINA FASHKI AND PARTNERS EXCHANGE COMPANY: FASHKI, Farzad (a.k.a. FESHKI, Farzad); FASHKI, Mina (a.k.a. FESHKI, Mina).
- RAHBAR BAZARGANI NESIM BAHARAN QESHM COMPANY: HEMMATI, Valiollah; JALALI, Sayyed Mohammad; KALHOR, Ali.

Entities (22 on the notice), mostly [IRAN-EO13902]:

- Iran-based exchange and monetary-intermediary entities: MELLAT EXCHANGE COMPANY; MINA FASHKI AND PARTNERS EXCHANGE COMPANY (a.k.a. MINA FASHKI AND PARTNERS GENERAL PARTNERSHIP COMPANY); RAHBAR BAZARGANI NESIM BAHARAN QESHM COMPANY; IRAN CENTER FOR EXCHANGE OF CURRENCY AND GOLD.
- Dubai (UAE) trading companies, including DEXTEROUS GLOBAL DMCC (a.k.a. ZANA INTERNATIONAL DMCC) and INTEGRAL PETRO ENERGY TRADING LLC (a.k.a. INTEGRAL PETRO ENERGY COMPANY; a.k.a. INTEGRAL PETRO ENERGY TRADING EST; linked to HMS TRADING FZE), plus ALAM AL SAHRA BUILDING MATERIALS TRADING CO. L.L.C, BERKELEY TRADING LLC, EWAN AL MADEENA GENERAL TRADING LLC, GESPL INTERNATIONAL GENERAL TRADING LLC, GRAND TARGET HEAVY EQUIPMENT AND MACHINERY SPARE PARTS TRADING L.L.C, H N B TRADING CO LLC, HEMRAJ TRADING L.L.C, KHORE AL HILAL GOODS WHOLESALERS TRADING LLC, MEETHALE RAW MATERIALS TRADING COMPANY LLC, NORDIC INTERNATIONAL TRADING LLC, OGA GLOBAL GENERAL TRADING L.L.C, RECAZ STAR GENERAL TRADING LLC, ROBUST TRADING LLC, ROYAH ALTAHABIA TRADING L.L.C.
- Hong Kong: GRANDEZ TRADING LIMITED.
- Turkey: BOGAZICI GUMRUKLEME ITHALAT IHRACAT TURIZM PETROL URUNLERI SANAYI VE TICARET LIMITED SIRKETI (Latin form with Turkish diacritics also printed).
- Program tags differ on two entries: H N B TRADING CO LLC carries [SDGT] [IFSR] (linked to SEPEHR ENERGY JAHAN NAMA PARS COMPANY, which also appears in the 2026-11-20 entry), and ROBUST TRADING LLC carries [IRAN-EO13871].

Identifier details printed in the notice (dates of birth, ID and registration numbers) are not reproduced here; read them at the source.

## Removals

None in this notice.

## Changes to existing entries

None in this notice.

## Matching notes

- Arabic script appears on nearly all entries: native-script matching is needed to resolve primary names, not only aliases.
- FASHKI / FESHKI is a vowel-shift transliteration pair on two separate individual entries that share a surname and a linked company. A shared surname does not make a query for one the other.
- Several Dubai entities carry near-identical generic trading-company names ("GENERAL TRADING LLC" and similar); legal-form suffixes (LLC, L.L.C, DMCC) vary, so suffix handling affects matching.
- Exchange-company names are short and descriptive; entity matching should be keyed to the full name as quoted, and this notice does not connect them to any similarly named party not listed.

## Fixtures

Eight cases, `WLD-2026-11-23-001` to `-008` in `tests/regression-cases.json`. Keyed to names as quoted in the notice; OFAC record IDs are not printed in web notices (see README, known limitations).
