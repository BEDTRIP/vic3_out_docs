---
type: concept
description: "Вид компании ««La Presse»» — Morgenröte 1.13, `pbi_company_la_presse`"
project: vic3
source: morgenrote
aliases: ["«La Presse»", "La Presse", "pbi_company_la_presse"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pbi_company_la_presse
paths: [Morgenrote/common/company_types/mr_manzoni_company_types.txt]
---
# «La Presse»

Вид компании · `pbi_company_la_presse` · `common/company_types/mr_manzoni_company_types.txt:236`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/pbi_la_presse_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_prints`
- **prestige_goods_trigger**: скрипт, строки 258–263
- **potential**: скрипт, строки 265–269
- **attainable**: скрипт, строки 271–275
- **possible**: скрипт, строки 277–287
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-petty-bourgeoisie-pop-attraction-mult|interest_group_ig_petty_bourgeoisie_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 294–299
- **ai_construction_targets**: скрипт, строки 301–308
- **ai_weight**: скрипт, строки 310–312
