---
type: concept
description: "Вид компании «Gazprom» — T&R 1.13, `company_gazprom`"
project: vic3
source: tr
aliases: ["Gazprom", "company_gazprom"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_gazprom
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# Gazprom

Вид компании · `company_gazprom` · `common/company_types/ztr_oil_gas_companies.txt:308`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/russian_company_gazprom.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_INGRIA`
- **building_types**: [[tr/Здания/Электростанции|Электростанции]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
- **possible_prestige_goods**: `prestige_good_gazprom_natural_gas`
- **extension_building_types**: [[tr/Здания/Oil Refineries|Oil Refineries]]
- **potential**: скрипт, строки 325–327
- **attainable**: скрипт, строки 328–336
- **possible**: скрипт, строки 337–345
- **prosperity_modifier**:
  - `building_natural_gas_rig_throughput_add` = `0.25` → [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-from-army-power-projection-mult|country_prestige_from_army_power_projection_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 351–356
- **ai_construction_targets**: скрипт, строки 357–367
- **ai_weight**: скрипт, строки 368–370
