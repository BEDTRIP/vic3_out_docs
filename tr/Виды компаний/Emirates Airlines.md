---
type: concept
description: "Вид компании «Emirates Airlines» — T&R 1.13, `company_emirates_airline`"
project: vic3
source: tr
aliases: ["Emirates Airlines", "company_emirates_airline"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_emirates_airline
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Emirates Airlines

Вид компании · `company_emirates_airline` · `common/company_types/ztr_airline_companies.txt:434`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/emirates.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ABU_DHABI`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 447–449
- **attainable**: скрипт, строки 450–457
- **possible**: скрипт, строки 458–468
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.05` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.1` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 475–481
- **ai_construction_targets**: скрипт, строки 482–489
- **ai_weight**: скрипт, строки 490–492
