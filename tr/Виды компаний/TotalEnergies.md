---
type: concept
description: "Вид компании «TotalEnergies» — T&R 1.13, `company_total`"
project: vic3
source: tr
aliases: ["TotalEnergies", "company_total"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_total
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# TotalEnergies

Вид компании · `company_total` · `common/company_types/ztr_oil_gas_companies.txt:138`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_company_total.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **potential**: скрипт, строки 153–155
- **attainable**: скрипт, строки 156–164
- **possible**: скрипт, строки 165–173
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.05` → [[tr/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы S#^m-state-colony-growth-speed-mult|state_colony_growth_speed_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 179–184
- **ai_weight**: скрипт, строки 185–187
