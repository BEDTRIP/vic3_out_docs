---
type: concept
description: "Вид компании «Saudi Aramco» — T&R 1.13, `company_saudi_aramco`"
project: vic3
source: tr
aliases: ["Saudi Aramco", "company_saudi_aramco"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_saudi_aramco
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# Saudi Aramco

Вид компании · `company_saudi_aramco` · `common/company_types/ztr_oil_gas_companies.txt:374`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/arabian_company_saudi_aramco.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEJD`, `STATE_ABU_DHABI`
- **building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]], [[tr/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: `prestige_good_saudi_aramco_oil`
- **potential**: скрипт, строки 394–396
- **attainable**: скрипт, строки 397–407
- **possible**: скрипт, строки 408–422
- **prosperity_modifier**:
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.15` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-mortality-wealth-mult|state_mortality_wealth_mult]] = `-0.002`
- **ai_will_do**: скрипт, строки 428–434
- **ai_construction_targets**: скрипт, строки 435–445
- **ai_weight**: скрипт, строки 446–448
