---
type: concept
description: "Вид компании ««La Vanguardia»» — Morgenröte 1.13, `pbi_company_la_vanguardia`"
project: vic3
source: morgenrote
aliases: ["«La Vanguardia»", "La Vanguardia", "pbi_company_la_vanguardia"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pbi_company_la_vanguardia
paths: [Morgenrote/common/company_types/mr_manzoni_company_types.txt]
---
# «La Vanguardia»

Вид компании · `pbi_company_la_vanguardia` · `common/company_types/mr_manzoni_company_types.txt:2075`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/pbi_la_vanguardia_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CATALONIA`
- **building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_prints`
- **prestige_goods_trigger**: скрипт, строки 2097–2102
- **potential**: скрипт, строки 2104–2108
- **attainable**: скрипт, строки 2110–2114
- **possible**: скрипт, строки 2116–2126
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-pop-attraction-mult|interest_group_ig_intelligentsia_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 2133–2138
- **ai_construction_targets**: скрипт, строки 2140–2147
- **ai_weight**: скрипт, строки 2149–2151
