---
type: concept
description: "Вид компании «Imperial Airways» — Morgenröte 1.13, `curtiss_company_imperial_airways`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Imperial Airways", "curtiss_company_imperial_airways"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_imperial_airways
paths: [Morgenrote/common/company_types/mr_curtiss_company_types.txt]
---
# Imperial Airways

Вид компании · `curtiss_company_imperial_airways` · `common/company_types/mr_curtiss_company_types.txt:222`

## Поля

- **icon**: `gfx/interface/icons/company_icons/curtiss_airline_imperial_airways_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[morgenrote/Здания/Аэропорты|Аэропорты]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_flights`
- **prestige_goods_trigger**: скрипт, строки 242–247
- **potential**: скрипт, строки 249–255
- **possible**: скрипт, строки 257–265
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `10`
- **ai_will_do**: скрипт, строки 272–278
- **ai_construction_targets**: скрипт, строки 280–287
- **ai_weight**: скрипт, строки 289–291
