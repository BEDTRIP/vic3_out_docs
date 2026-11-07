---
type: concept
description: "Вид компании «General Motors» — T&R 1.13, `company_general_motors`"
project: vic3
source: tr
aliases: ["General Motors", "company_general_motors"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_general_motors
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# General Motors

Вид компании · `company_general_motors` · `common/company_types/ztr_automotive_companies.txt:865`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_general_motors.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MICHIGAN`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Оружейные заводы|Оружейные заводы]]
- **possible_prestige_goods**: `prestige_good_ford_automobiles`
- **potential**: скрипт, строки 882–884
- **attainable**: скрипт, строки 885–891
- **possible**: скрипт, строки 892–902
- **prosperity_modifier**:
  - `building_railway_throughput_add` = `-0.15` → [[tr/Здания/Железные дороги|Железные дороги]]
  - `state_infrastructure_from_automobiles_consumption_add` = `0.15`
  - `building_group_bg_heavy_industry_throughput_add` = `0.01`
- **ai_will_do**: скрипт, строки 908–914
- **ai_construction_targets**: скрипт, строки 915–922
- **ai_weight**: скрипт, строки 923–925
