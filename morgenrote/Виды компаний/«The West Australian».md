---
type: concept
description: "Вид компании ««The West Australian»» — Morgenröte 1.15, `pbi_company_the_west_australian`"
project: vic3
audience: agent
source: morgenrote
aliases: ["«The West Australian»", "The West Australian", "pbi_company_the_west_australian"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pbi_company_the_west_australian
paths: [Morgenrote/common/company_types/mr_manzoni_company_types.txt]
---
# «The West Australian»

Вид компании · `pbi_company_the_west_australian` · `common/company_types/mr_manzoni_company_types.txt:1357`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/pbi_the_west_australian_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WESTERN_AUSTRALIA`
- **building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_prints`
- **prestige_goods_trigger**: скрипт, строки 1379–1384
- **potential**: скрипт, строки 1386–1390
- **attainable**: скрипт, строки 1392–1396
- **possible**: скрипт, строки 1398–1408
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pop-attraction-mult|interest_group_ig_landowners_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-mult|country_bureaucracy_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 1415–1420
- **ai_construction_targets**: скрипт, строки 1422–1429
- **ai_weight**: скрипт, строки 1431–1433
