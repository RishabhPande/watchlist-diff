# 2026-11-18 - SDN: Counter Terrorism Designations ("Operation Economic Outcast")

- **Source:** OFAC Recent Actions - https://ofac.treasury.gov/recent-actions/20261118
- **Release date:** 11/18/2026
- OFAC's notice is headed "Operation Economic Outcast Targets Iran's Proxy Networks"; all additions are [SDGT] and linked to HIZBALLAH, with secondary-sanctions risk under section 1(b) of EO 13224 as amended.

## Additions

Individuals:

- **CHOUMAN, Afif Abdel Rida** (a.k.a. AL-FADL, Abu; a.k.a. SHUMAN, Afif Abd-Al-Rida), Lebanon; linked to HIZBALLAH.
- **KHECHEN, Hassan** (a.k.a. KHASHAN, Hassan; a.k.a. KHASHAN, Hassan Muhammad), Lebanon; linked to HIZBALLAH.
- **KHECHEN, Ibrahim**, Lebanon; linked to HIZBALLAH.

Entities:

- **GOLD GLOBAL COMPANY** (a.k.a. GOLD GLOBAL COMPANY HASSAN MOHAMAD KHECHEN AND HIS PARTNERS), Sidon, Lebanon; metals wholesale; linked to KHECHEN, Hassan.
- **SANKARI GOLD KUYUMCULUK TICARET LIMITED SIRKETI** (a.k.a. SANKARI GOLD JEWELRY TRADE LIMITED COMPANY), Istanbul, Turkey; jewelry and precious-metals wholesale; linked to KHECHEN, Hassan.
- **WA TA'AWANU ASSOCIATION** (a.k.a. WA TAAWANOU), Zefta, Nabatieh, Lebanon; linked to HIZBALLAH.

## Removals

None in this notice.

## Changes to existing entries

None in this notice.

## Matching notes

- Apostrophe/orthography variants: WA TA'AWANU ASSOCIATION's alias WA TAAWANOU drops the apostrophe entirely; matchers keyed to exact punctuation would miss it.
- Descriptive alias form: GOLD GLOBAL COMPANY's alias embeds the owner's full name ("...HASSAN MOHAMAD KHECHEN AND HIS PARTNERS") - an individual's name string inside an entity alias.
- Name-order sensitivity: CHOUMAN's alias SHUMAN, Afif Abd-Al-Rida changes both the surname transliteration and the hyphenation of the given names.

## Fixtures

Six cases, `WLD-2026-11-18-001` to `-006` in `tests/regression-cases.json`. Keyed to names as quoted in the notice; OFAC record IDs are not printed in web notices (see README, known limitations).
