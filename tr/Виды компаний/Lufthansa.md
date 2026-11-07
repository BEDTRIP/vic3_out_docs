---
type: concept
description: "Вид компании «Lufthansa» — T&R 1.13, `curtiss_company_DLR`"
project: vic3
source: tr
aliases: ["Lufthansa", "curtiss_company_DLR"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_DLR
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Lufthansa

Вид компании · `curtiss_company_DLR` · `common/company_types/ztr_airline_companies.txt:68`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/curtiss_airline_dlr_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRANDENBURG`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 81–83
- **attainable**: скрипт, строки 84–91
- **possible**: скрипт, строки 92–101
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 107–112
- **ai_construction_targets**: скрипт, строки 113–120
- **ai_weight**: скрипт, строки 121–123
