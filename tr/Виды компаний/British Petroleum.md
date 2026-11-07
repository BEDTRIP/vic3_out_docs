---
type: concept
description: "Вид компании «British Petroleum» — T&R 1.13, `company_bg`"
project: vic3
source: tr
aliases: ["British Petroleum", "company_bg"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bg
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# British Petroleum

Вид компании · `company_bg` · `common/company_types/ztr_oil_gas_companies.txt:191`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/british_company_bg.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]], [[tr/Здания/Заводы удобрений|Заводы удобрений]]
- **potential**: скрипт, строки 207–209
- **attainable**: скрипт, строки 210–218
- **possible**: скрипт, строки 219–227
- **prosperity_modifier**:
  - `building_natural_gas_rig_throughput_add` = `0.1` → [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
  - [[vanilla/движок/Модификаторы S#^m-state-colony-growth-speed-mult|state_colony_growth_speed_mult]] = `0.15`
- **ai_will_do**: скрипт, строки 232–237
- **ai_weight**: скрипт, строки 238–240
