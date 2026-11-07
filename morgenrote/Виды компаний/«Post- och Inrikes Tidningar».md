---
type: concept
description: "Вид компании ««Post- och Inrikes Tidningar»» — Morgenröte 1.13, `pbi_company_post_och_inrikes_tidningar`"
project: vic3
source: morgenrote
aliases: ["«Post- och Inrikes Tidningar»", "Post- och Inrikes Tidningar", "pbi_company_post_och_inrikes_tidningar"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pbi_company_post_och_inrikes_tidningar
paths: [Morgenrote/common/company_types/mr_manzoni_company_types.txt]
---
# «Post- och Inrikes Tidningar»

Вид компании · `pbi_company_post_och_inrikes_tidningar` · `common/company_types/mr_manzoni_company_types.txt:2315`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/pbi_post_och_inrikes_tidningar_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_prints`
- **prestige_goods_trigger**: скрипт, строки 2337–2342
- **potential**: скрипт, строки 2344–2348
- **attainable**: скрипт, строки 2350–2354
- **possible**: скрипт, строки 2356–2366
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pop-attraction-mult|interest_group_ig_landowners_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-mult|country_bureaucracy_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 2373–2378
- **ai_construction_targets**: скрипт, строки 2380–2387
- **ai_weight**: скрипт, строки 2389–2391
