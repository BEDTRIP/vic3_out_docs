---
type: concept
description: "Вид компании «BYD» — T&R 1.13, `company_byd`"
project: vic3
source: tr
aliases: ["BYD", "company_byd"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_byd
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# BYD

Вид компании · `company_byd` · `common/company_types/ztr_automotive_companies.txt:84`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_byd.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_GUANGDONG`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Battery Plants|Battery Plants]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Renewable Energy Power Plants|Renewable Energy Power Plants]]
- **possible_prestige_goods**: `prestige_good_asia_automobiles`
- **prestige_goods_trigger**: скрипт, строки 102–107
- **potential**: скрипт, строки 108–110
- **attainable**: скрипт, строки 111–117
- **possible**: скрипт, строки 118–128
- **prosperity_modifier**:
  - `building_electronics_industry_throughput_add` = `0.1` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
  - `building_processors_foundry_throughput_add` = `0.1` → [[tr/Здания/Chip Foundries|Chip Foundries]]
  - `state_infrastructure_from_automobiles_consumption_add` = `0.1`
- **ai_will_do**: скрипт, строки 134–140
- **ai_construction_targets**: скрипт, строки 141–148
- **ai_weight**: скрипт, строки 149–151
