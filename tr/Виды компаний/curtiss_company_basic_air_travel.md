---
type: concept
description: "Вид компании «curtiss_company_basic_air_travel» — T&R 1.13, `curtiss_company_basic_air_travel`"
project: vic3
audience: agent
source: tr
aliases: ["curtiss_company_basic_air_travel"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: curtiss_company_basic_air_travel
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# curtiss_company_basic_air_travel

Вид компании · `curtiss_company_basic_air_travel` · `common/company_types/ztr_99_basic_companies.txt:144`

## Поля

- **icon**: `gfx/interface/icons/company_icons/curtiss_airline_generic_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **possible**: скрипт, строки 162–171
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 179–188
