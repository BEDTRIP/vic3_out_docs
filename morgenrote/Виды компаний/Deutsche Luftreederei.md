---
type: concept
description: "Вид компании «Deutsche Luftreederei» — Morgenröte 1.13, `curtiss_company_DLR`"
project: vic3
source: morgenrote
aliases: ["Deutsche Luftreederei", "curtiss_company_DLR"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_DLR
paths: [Morgenrote/common/company_types/mr_curtiss_company_types.txt]
---
# Deutsche Luftreederei

Вид компании · `curtiss_company_DLR` · `common/company_types/mr_curtiss_company_types.txt:136`

## Поля

- **icon**: `gfx/interface/icons/company_icons/curtiss_airline_dlr_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRANDENBURG`
- **building_types**: [[morgenrote/Здания/Аэропорты|Аэропорты]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_flights`
- **prestige_goods_trigger**: скрипт, строки 156–161
- **potential**: скрипт, строки 163–176
- **possible**: скрипт, строки 178–186
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `10`
- **ai_will_do**: скрипт, строки 193–205
- **ai_construction_targets**: скрипт, строки 207–214
- **ai_weight**: скрипт, строки 216–218
