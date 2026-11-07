---
type: concept
description: "Вид компании «Rolls-Royce» — T&R 1.13, `company_rolls_royce`"
project: vic3
audience: agent
source: tr
aliases: ["Rolls-Royce", "company_rolls_royce"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rolls_royce
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Rolls-Royce

Вид компании · `company_rolls_royce` · `common/company_types/ztr_automotive_companies.txt:989`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/british_rolls_royce.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **potential**: скрипт, строки 1000–1002
- **attainable**: скрипт, строки 1003–1009
- **possible**: скрипт, строки 1010–1020
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.1` → [[tr/Здания/верфи|верфи]]
  - `building_aircraft_industry_throughput_add` = `0.1` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
- **ai_will_do**: скрипт, строки 1025–1031
- **ai_construction_targets**: скрипт, строки 1032–1039
- **ai_weight**: скрипт, строки 1040–1042
