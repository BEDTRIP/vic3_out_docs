---
type: concept
description: "Вид компании «Air China» — T&R 1.13, `company_air_china`"
project: vic3
audience: agent
source: tr
aliases: ["Air China", "company_air_china"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_air_china
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Air China

Вид компании · `company_air_china` · `common/company_types/ztr_airline_companies.txt:496`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/air_china.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BEIJING`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 509–511
- **attainable**: скрипт, строки 512–519
- **possible**: скрипт, строки 520–530
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 536–542
- **ai_construction_targets**: скрипт, строки 543–550
- **ai_weight**: скрипт, строки 551–553
