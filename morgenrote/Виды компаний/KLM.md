---
type: concept
description: "Вид компании «KLM» — Morgenröte 1.13, `curtiss_company_KLM`"
project: vic3
source: morgenrote
aliases: ["KLM", "curtiss_company_KLM"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_KLM
paths: [Morgenrote/common/company_types/mr_curtiss_company_types.txt]
---
# KLM

Вид компании · `curtiss_company_KLM` · `common/company_types/mr_curtiss_company_types.txt:56`

## Поля

- **icon**: `gfx/interface/icons/company_icons/curtiss_airline_klm_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`, `STATE_GELRE`
- **building_types**: [[morgenrote/Здания/Аэропорты|Аэропорты]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_flights`
- **prestige_goods_trigger**: скрипт, строки 78–83
- **potential**: скрипт, строки 85–90
- **possible**: скрипт, строки 92–104
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `10`
- **ai_will_do**: скрипт, строки 111–119
- **ai_construction_targets**: скрипт, строки 121–128
- **ai_weight**: скрипт, строки 130–132
