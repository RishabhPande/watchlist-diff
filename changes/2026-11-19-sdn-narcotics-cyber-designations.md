# 2026-11-19 - SDN: Counter Narcotics and Cyber-related Designations (plus general licenses)

- **Source:** OFAC Recent Actions - https://ofac.treasury.gov/recent-actions/20261119
- **Release date:** 11/19/2026
- Same notice also issued Illicit Drugs General License 1 (wind-down of transactions involving certain persons blocked 19 Nov 2026) and Russia-related General License 131L (Lukoil International GmbH contingent-contract negotiation), with amended FAQs 1224 and 1225. General licenses are permissions, not list changes; no fixtures derive from them.

## Additions

Individuals, counter-narcotics [ILLICIT-DRUGS-EO14059] unless noted:

- **COFFEN, Marco Francis** (a.k.a. DE BERNARDO, Marco Sullivan), Italy / UAE; linked to COMANCHERO OUTLAW MOTORCYCLE GANG.
- **COMMISSO, Francesco** (a.k.a. "U Scelto"), Ontario, Canada / Siderno, Italy; linked to 'NDRANGHETA.
- **COMMISSO, Rocco Remo**, Ontario, Canada; linked to 'NDRANGHETA.
- **DEMARIA, Vincenzo** (a.k.a. DEMARIA, Jimmy), Ontario, Canada; linked to 'NDRANGHETA.
- **FIGLIOMENI, Angelo** (a.k.a. "Don Angelino"), Vaughan, Ontario, Canada; linked to 'NDRANGHETA.
- **FIGLIOMENI, Cosimo** (a.k.a. "Cosimino"; a.k.a. "Mino"), Ontario, Canada; linked to 'NDRANGHETA.
- **MEEHAN, Allan John Norman** (a.k.a. MEEHAN, Allan), Australia; linked to COMANCHERO OUTLAW MOTORCYCLE GANG.
- **NAUFAHU, Pasilika** (a.k.a. "Lika"), New Zealand; linked to COMANCHERO OUTLAW MOTORCYCLE GANG.
- **NAUFAHU, Vetekina** (a.k.a. "Kina"), New Zealand; linked to COMANCHERO OUTLAW MOTORCYCLE GANG.
- **VARELA VILLAR, Alexandre** (a.k.a. VARE, Alex; a.k.a. VARELA, Alex), Spain; TRX digital-currency address on entry; linked to COMANCHERO OUTLAW MOTORCYCLE GANG.
- **VESCIO SR., Luigi** (a.k.a. VESCIO, Lui; a.k.a. "The Undertaker"), Ontario, Canada; linked to 'NDRANGHETA.
- **VESCIO JR., Luigi**, Ontario, Canada; linked to VESCIO SR., Luigi.
- **VESCIO, Laura** (a.k.a. VESCIO-SACCO, Laura), Ontario, Canada; linked to VESCIO SR., Luigi.
- **VESCIO, Rose** (a.k.a. VESCIO, Rosa Maria), Ontario, Canada; linked to VESCIO SR., Luigi.

Individuals, cyber-related [CYBER4]:

- **ONE, Saw A** (a.k.a. "ONE, Saw Eh"; a.k.a. "WAH, Saw Ew"), Karen State, Burma; linked to DEMOCRATIC KAREN BENEVOLENT ARMY.
- **WAH, Saw Shwe** (a.k.a. WAH, Maung Shwe; a.k.a. "WA, Saw Shwe"; a.k.a. "WAH, Swe"), Kayin State, Burma; linked to DEMOCRATIC KAREN BENEVOLENT ARMY.
- **ZHAO, Hui**, Tokyo, Japan; nationality Cambodia / China.

Entities:

- **COMANCHERO OUTLAW MOTORCYCLE GANG** (a.k.a. COMANCHERO MOTORCYCLE CLUB; a.k.a. "COMANCHERO MC"), Australia; New Zealand; Spain; Bosnia and Herzegovina; Germany; criminal organization [ILLICIT-DRUGS-EO14059].
- **FRATELLI VESCIO FUNERAL HOMES LTD.**, Woodbridge, Ontario, Canada; linked to VESCIO SR., Luigi.
- **PHANTOM LIMOUSINE SERVICES INC.**, Woodbridge, Ontario, Canada; linked to VESCIO SR., Luigi.
- **VESCIO FUNERAL HOME MAPLE INC.**, Maple, Ontario, Canada; linked to VESCIO SR., Luigi.
- **VESCIO FUNERAL HOMES INC.**, Toronto, Ontario, Canada; linked to VESCIO SR., Luigi.
- **BEI FANG BO LIN CONSTRUCTION DECORATION CO., LTD.**, Phnom Penh, Cambodia; [CYBER4], linked to ZHAO, Hui.
- **ZHZ INVESTMENT CONSULTING CO., LTD.**, Phnom Penh, Cambodia; [CYBER4], linked to ZHAO, Hui.

## Removals

None in this notice.

## Changes to existing entries

- **'NDRANGHETA ORGANIZATION** (Italy) was republished as **'NDRANGHETA** (Italy), with Target Type Criminal Organization and the [ILLICIT-DRUGS-EO14059] tag added; [SDNTK] retained. The party remains designated; this is an entry change, not an addition or removal.

## Matching notes

- Name supersession: screening keyed to the exact string "'NDRANGHETA ORGANIZATION" now matches a name no longer on the entry; historical queries using it resolve to the same listed party. The leading apostrophe itself is an orthographic hazard for exact matchers.
- Nickname aliases in quotes ("U Scelto", "The Undertaker", "Don Angelino", "Lika", "Kina") are full alias strings, including one English-language nickname attached to an Italian-Canadian individual.
- Front-company pattern: four Ontario entities (funeral homes, limousine services) carry ordinary business names with no lexical link to the listed individual - entity-name matching alone cannot surface the linkage.
- Alias surname swap: COFFEN's alias DE BERNARDO, Marco Sullivan shares no surname with the primary name.
- Near-identical sibling names: VESCIO SR., Luigi and VESCIO JR., Luigi are distinct listed parties; suffix-only differentiation.
- The VARELA VILLAR entry includes a TRX digital-currency address as an identifier - a non-name identifier class on an SDN entry.

## Fixtures

Eight cases, `WLD-2026-11-19-001` to `-008` in `tests/regression-cases.json`. Keyed to names as quoted in the notice; OFAC record IDs are not printed in web notices (see README, known limitations).
