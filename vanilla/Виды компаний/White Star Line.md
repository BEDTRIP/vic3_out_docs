---
type: concept
description: "Вид компании «White Star Line» — ваниль 1.13, `company_white_star_line`"
project: vic3
audience: agent
source: vanilla
aliases: ["White Star Line", "company_white_star_line"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_white_star_line
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# White Star Line

Вид компании · `company_white_star_line` · `common/company_types/00_companies_ep2.txt:1206`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_white_star_line.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LANCASHIRE`
- **building_types**: [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vanilla/Здания/верфи|верфи]]
- **possible_prestige_goods**: `prestige_good_white_star_liners`
- **potential**: скрипт, строки 1226–1229
- **attainable**: скрипт, строки 1231–1237
- **possible**: скрипт, строки 1239–1249
- **ai_will_do**: скрипт, строки 1251–1258
- **ai_construction_targets**: скрипт, строки 1260–1267
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.15`
- **ai_weight**: скрипт, строки 1274–1276
