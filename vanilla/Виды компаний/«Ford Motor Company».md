---
type: concept
description: "Вид компании ««Ford Motor Company»» — ваниль 1.15, `company_ford_motor`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Ford Motor Company»", "Ford Motor Company", "company_ford_motor"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ford_motor
paths: [.vanillaVIC3/common/company_types/00_companies_usa.txt]
---
# «Ford Motor Company»

Вид компании · `company_ford_motor` · `common/company_types/00_companies_usa.txt:418`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_ford.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MICHIGAN`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]]
- **possible_prestige_goods**: `prestige_good_ford_automobiles`
- **potential**: скрипт, строки 440–442
- **attainable**: скрипт, строки 444–450
- **possible**: скрипт, строки 452–460
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.15` → [[vanilla/Здания/Моторные заводы|Моторные заводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.05` → [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **ai_will_do**: скрипт, строки 467–473
- **ai_construction_targets**: скрипт, строки 475–482
- **ai_weight**: скрипт, строки 484–486
