---
type: concept
description: "Вид компании ««Bunge y Born»» — ваниль 1.15, `company_bunge_born`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Bunge y Born»", "Bunge & Born", "company_bunge_born"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bunge_born
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «Bunge y Born»

Вид компании · `company_bunge_born` · `common/company_types/00_companies_americas.txt:297`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/argentina_bunge_y_born.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Маисовые поля|Маисовые поля]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **prestige_goods_trigger**: скрипт, строки 317–322
- **potential**: скрипт, строки 324–326
- **attainable**: скрипт, строки 328–334
- **possible**: скрипт, строки 336–349
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-rural-folk-pop-attraction-mult|interest_group_ig_rural_folk_pop_attraction_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы B#^m-building-tooling-workshop-throughput-add|building_tooling_workshop_throughput_add]] = `0.1` → [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **ai_will_do**: скрипт, строки 356–361
- **ai_construction_targets**: скрипт, строки 363–378
- **ai_weight**: скрипт, строки 380–382
