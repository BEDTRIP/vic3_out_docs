---
type: concept
description: "Вид компании «Toyota» — T&R 1.13, `company_toyota`"
project: vic3
source: tr
aliases: ["Toyota", "company_toyota"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_toyota
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Toyota

Вид компании · `company_toyota` · `common/company_types/ztr_automotive_companies.txt:155`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_toyota.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_TOKAI`
- **building_types**: [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Robotics Industries|Robotics Industries]], [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **possible_prestige_goods**: `prestige_good_asia_automobiles`
- **prestige_goods_trigger**: скрипт, строки 174–179
- **potential**: скрипт, строки 180–182
- **attainable**: скрипт, строки 183–189
- **possible**: скрипт, строки 190–200
- **prosperity_modifier**:
  - `building_battery_plant_throughput_add` = `0.1` → [[tr/Здания/Battery Plants|Battery Plants]]
  - `building_automotive_industry_throughput_add` = `0.05` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **ai_will_do**: скрипт, строки 205–211
- **ai_construction_targets**: скрипт, строки 212–219
- **ai_weight**: скрипт, строки 220–222
