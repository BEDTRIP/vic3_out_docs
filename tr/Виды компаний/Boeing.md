---
type: concept
description: "Вид компании «Boeing» — T&R 1.13, `company_boeing`"
project: vic3
source: tr
aliases: ["Boeing", "company_boeing"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_boeing
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_airline_companies.txt]
---
# Boeing

Вид компании · `company_boeing` · `common/company_types/ztr_airline_companies.txt:557`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/boeing.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_airline.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_VIRGINIA`
- **building_types**: [[tr/Здания/Aerospace Industries|Aerospace Industries]]
- **extension_building_types**: [[tr/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **possible_prestige_goods**: `prestige_good_boeing_aircraft`
- **potential**: скрипт, строки 573–575
- **attainable**: скрипт, строки 576–583
- **possible**: скрипт, строки 584–593
- **prosperity_modifier**:
  - `building_airport_throughput_add` = `0.25` → [[tr/Здания/Airports|Airports]]
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.05` → [[tr/Здания/Моторные заводы|Моторные заводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-artillery-foundry-throughput-add|building_artillery_foundry_throughput_add]] = `0.05` → [[tr/Здания/Артиллерийские заводы|Артиллерийские заводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `-0.1` → [[tr/Здания/Железные дороги|Железные дороги]]
- **ai_will_do**: скрипт, строки 601–606
- **ai_construction_targets**: скрипт, строки 607–614
- **ai_weight**: скрипт, строки 615–617
