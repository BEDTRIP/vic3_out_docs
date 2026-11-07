---
type: concept
description: "Вид компании «BMW» — T&R 1.13, `company_bmw`"
project: vic3
source: tr
aliases: ["BMW", "company_bmw"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bmw
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# BMW

Вид компании · `company_bmw` · `common/company_types/ztr_automotive_companies.txt:555`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_bmw.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAVARIA`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 572–574
- **attainable**: скрипт, строки 575–581
- **possible**: скрипт, строки 582–592
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.1` → [[tr/Здания/Моторные заводы|Моторные заводы]]
  - `building_alloys_plant_throughput_add` = `0.05` → [[tr/Здания/Alloys Plants|Alloys Plants]]
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.25`
- **ai_will_do**: скрипт, строки 598–604
- **ai_construction_targets**: скрипт, строки 605–612
- **ai_weight**: скрипт, строки 613–615
