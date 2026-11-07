---
type: concept
description: "Вид компании «Airbus» — T&R 1.13, `company_airbus`"
project: vic3
audience: agent
source: tr
aliases: ["Airbus", "company_airbus"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_airbus
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Airbus

Вид компании · `company_airbus` · `common/company_types/ztr_airline_companies.txt:621`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/airbus.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Aerospace Industries|Aerospace Industries]]
- **extension_building_types**: [[tr/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **possible_prestige_goods**: `prestige_good_airbus_aircraft`
- **potential**: скрипт, строки 638–644
- **attainable**: скрипт, строки 645–657
- **possible**: скрипт, строки 658–684
- **prosperity_modifier**:
  - `building_airport_throughput_add` = `0.25` → [[tr/Здания/Airports|Airports]]
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.05` → [[tr/Здания/Моторные заводы|Моторные заводы]]
- **ai_will_do**: скрипт, строки 690–700
- **ai_construction_targets**: скрипт, строки 701–713
- **ai_weight**: скрипт, строки 714–716
