---
type: concept
description: "Вид компании «Rio Tinto» — T&R 1.13, `company_rio_tinto`"
project: vic3
audience: agent
source: tr
aliases: ["Rio Tinto", "company_rio_tinto"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rio_tinto
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# Rio Tinto

Вид компании · `company_rio_tinto` · `common/company_types/ztr_mining_companies.txt:671`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/rio_tinto.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_UPPER_ANDALUSIA`, `STATE_NEW_SOUTH_WALES`, `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Rare Earths Mines|Rare Earths Mines]], [[tr/Здания/Copper Mines|Copper Mines]], [[tr/Здания/Bauxite Mines|Bauxite Mines]]
- **extension_building_types**: [[tr/Здания/Железные рудники|Железные рудники]]
- **potential**: скрипт, строки 688–692
- **attainable**: скрипт, строки 693–702
- **possible**: скрипт, строки 703–715
- **prosperity_modifier**:
  - `building_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
  - `building_battery_plant_throughput_add` = `0.05` → [[tr/Здания/Battery Plants|Battery Plants]]
- **ai_will_do**: скрипт, строки 720–727
- **ai_construction_targets**: скрипт, строки 728–737
- **ai_weight**: скрипт, строки 738–740
