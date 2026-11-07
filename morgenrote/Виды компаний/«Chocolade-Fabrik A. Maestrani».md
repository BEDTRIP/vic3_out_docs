---
type: concept
description: "Вид компании ««Chocolade-Fabrik A. Maestrani»» — Morgenröte 1.13, `company_maestrani`"
project: vic3
audience: agent
source: morgenrote
aliases: ["«Chocolade-Fabrik A. Maestrani»", "Chocolade-Fabrik A. Maestrani", "company_maestrani"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_maestrani
paths: [Morgenrote/common/company_types/mr_company_types.txt]
---
# «Chocolade-Fabrik A. Maestrani»

Вид компании · `company_maestrani` · `common/company_types/mr_company_types.txt:75`

## Поля

- **icon**: `gfx/interface/icons/company_icons/mr_food_maestrani.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EAST_SWITZERLAND`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]], [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]]
- **possible_prestige_goods**: `prestige_good_swiss_chocolate`
- **potential**: скрипт, строки 97–99
- **possible**: скрипт, строки 101–110
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
  - [[vanilla/движок/Модификаторы S#^m-state-upper-strata-standard-of-living-add|state_upper_strata_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 117–122
- **ai_construction_targets**: скрипт, строки 124–131
- **ai_weight**: скрипт, строки 133–135
