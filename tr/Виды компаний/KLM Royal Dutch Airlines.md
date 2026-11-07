---
type: concept
description: "Вид компании «KLM Royal Dutch Airlines» — T&R 1.13, `curtiss_company_KLM`"
project: vic3
source: tr
aliases: ["KLM Royal Dutch Airlines", "curtiss_company_KLM"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_KLM
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# KLM Royal Dutch Airlines

Вид компании · `curtiss_company_KLM` · `common/company_types/ztr_airline_companies.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/curtiss_airline_klm_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`, `STATE_GELRE`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 16–18
- **attainable**: скрипт, строки 19–26
- **possible**: скрипт, строки 27–39
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - `state_infrastructure_from_population_add` = `2`
  - `state_infrastructure_from_population_max_add` = `8`
- **ai_will_do**: скрипт, строки 45–53
- **ai_construction_targets**: скрипт, строки 54–61
- **ai_weight**: скрипт, строки 62–64
