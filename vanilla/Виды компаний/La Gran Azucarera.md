---
type: concept
description: "Вид компании «La Gran Azucarera» — ваниль 1.15, `company_gran_azucarera`"
project: vic3
audience: agent
source: vanilla
aliases: ["La Gran Azucarera", "company_gran_azucarera"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_gran_azucarera
paths: [.vanillaVIC3/common/company_types/00_companies_ip4.txt]
---
# La Gran Azucarera

Вид компании · `company_gran_azucarera` · `common/company_types/00_companies_ip4.txt:165`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_la_gran_azucarera.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: `prestige_good_havana_sugar`
- **potential**: скрипт, строки 187–190
- **attainable**: скрипт, строки 192–202
- **possible**: скрипт, строки 204–217
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-efficiency-mult|state_aristocrats_investment_pool_efficiency_mult]] = `0.15`
- **ai_will_do**: скрипт, строки 224–233
- **ai_construction_targets**: скрипт, строки 235–246
- **ai_weight**: скрипт, строки 248–250
