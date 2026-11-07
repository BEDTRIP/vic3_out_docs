---
type: concept
description: "Вид компании «China Rare Earth Group» — T&R 1.13, `company_china_rare_earth_group`"
project: vic3
source: tr
aliases: ["China Rare Earth Group", "company_china_rare_earth_group"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_china_rare_earth_group
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# China Rare Earth Group

Вид компании · `company_china_rare_earth_group` · `common/company_types/ztr_mining_companies.txt:744`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/china_rare_earth_group.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SHANXI`, `STATE_JIANGXI`, `STATE_HINGGAN`
- **building_types**: [[tr/Здания/Rare Earths Mines|Rare Earths Mines]], [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]]
- **extension_building_types**: [[tr/Здания/Bauxite Mines|Bauxite Mines]], [[tr/Здания/Copper Mines|Copper Mines]]
- **potential**: скрипт, строки 761–764
- **attainable**: скрипт, строки 765–776
- **possible**: скрипт, строки 777–790
- **prosperity_modifier**:
  - `building_consumer_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]]
  - `building_battery_plant_throughput_add` = `0.1` → [[tr/Здания/Battery Plants|Battery Plants]]
  - `state_birth_rate_mult` = `0.05`
- **ai_will_do**: скрипт, строки 796–805
- **ai_construction_targets**: скрипт, строки 806–826
- **ai_weight**: скрипт, строки 827–829
