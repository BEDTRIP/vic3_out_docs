---
type: concept
description: "Вид компании «Swissair» — Morgenröte 1.15, `curtiss_company_swissair`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Swissair", "curtiss_company_swissair"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_swissair
paths: [Morgenrote/common/company_types/mr_curtiss_company_types.txt]
---
# Swissair

Вид компании · `curtiss_company_swissair` · `common/company_types/mr_curtiss_company_types.txt:367`

## Поля

- **icon**: `gfx/interface/icons/company_icons/curtiss_airline_swissair_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EAST_SWITZERLAND`
- **building_types**: [[morgenrote/Здания/Аэропорты|Аэропорты]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_flights`
- **prestige_goods_trigger**: скрипт, строки 387–392
- **potential**: скрипт, строки 394–400
- **possible**: скрипт, строки 402–410
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `10`
- **ai_will_do**: скрипт, строки 417–422
- **ai_construction_targets**: скрипт, строки 424–431
- **ai_weight**: скрипт, строки 433–435
