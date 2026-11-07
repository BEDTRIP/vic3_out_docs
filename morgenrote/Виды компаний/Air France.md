---
type: concept
description: "Вид компании «Air France» — Morgenröte 1.13, `curtiss_company_air_france`"
project: vic3
source: morgenrote
aliases: ["Air France", "curtiss_company_air_france"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_air_france
paths: [Morgenrote/common/company_types/mr_curtiss_company_types.txt]
---
# Air France

Вид компании · `curtiss_company_air_france` · `common/company_types/mr_curtiss_company_types.txt:295`

## Поля

- **icon**: `gfx/interface/icons/company_icons/curtiss_airline_air_france_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[morgenrote/Здания/Аэропорты|Аэропорты]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_flights`
- **prestige_goods_trigger**: скрипт, строки 315–320
- **potential**: скрипт, строки 322–328
- **possible**: скрипт, строки 330–338
- **prosperity_modifier**:
  - `state_infrastructure_from_population_add` = `0.2`
  - `state_infrastructure_from_population_max_add` = `10`
- **ai_will_do**: скрипт, строки 345–350
- **ai_construction_targets**: скрипт, строки 352–359
- **ai_weight**: скрипт, строки 361–363
