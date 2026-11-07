---
type: concept
description: "Вид компании «Türk Hava Yollari (Turkish Airlines)» — T&R 1.13, `company_turk_hava_yollari_turkish`"
project: vic3
audience: agent
source: tr
aliases: ["Türk Hava Yollari (Turkish Airlines)", "company_turk_hava_yollari_turkish"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_turk_hava_yollari_turkish
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Türk Hava Yollari (Turkish Airlines)

Вид компании · `company_turk_hava_yollari_turkish` · `common/company_types/ztr_airline_companies.txt:373`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_turk_hava_yollari_turkish.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ANKARA`
- **building_types**: [[tr/Здания/Airports|Airports]]
- **potential**: скрипт, строки 386–388
- **attainable**: скрипт, строки 389–396
- **possible**: скрипт, строки 397–407
- **prosperity_modifier**:
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `2`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `8`
- **ai_will_do**: скрипт, строки 413–419
- **ai_construction_targets**: скрипт, строки 420–427
- **ai_weight**: скрипт, строки 428–430
