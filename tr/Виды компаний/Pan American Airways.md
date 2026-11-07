---
type: concept
description: "Вид компании «Pan American Airways» — T&R 1.13, `company_pan_american_airways`"
project: vic3
audience: agent
source: tr
aliases: ["Pan American Airways", "company_pan_american_airways"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_pan_american_airways
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Pan American Airways

Вид компании · `company_pan_american_airways` · `common/company_types/ztr_airline_companies.txt:304`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_pan_american_airways.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FLORIDA`, `STATE_PANAMA`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 318–320
- **attainable**: скрипт, строки 321–331
- **possible**: скрипт, строки 332–345
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 351–358
- **ai_construction_targets**: скрипт, строки 359–366
- **ai_weight**: скрипт, строки 367–369
