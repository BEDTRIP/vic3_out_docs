---
type: concept
description: "Вид компании «Air France» — T&R 1.13, `curtiss_company_air_france`"
project: vic3
audience: agent
source: tr
aliases: ["Air France", "curtiss_company_air_france"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_air_france
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Air France

Вид компании · `curtiss_company_air_france` · `common/company_types/ztr_airline_companies.txt:186`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/curtiss_airline_air_france_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 199–201
- **attainable**: скрипт, строки 202–209
- **possible**: скрипт, строки 210–219
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 225–230
- **ai_construction_targets**: скрипт, строки 231–238
- **ai_weight**: скрипт, строки 239–241
