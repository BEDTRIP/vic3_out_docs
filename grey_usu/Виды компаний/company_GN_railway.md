---
type: concept
description: "Вид компании «company_GN_railway» — grey USU 1.13, `company_GN_railway`"
project: vic3
source: grey_usu
aliases: ["company_GN_railway"]
tags: [grey_usu, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_GN_railway
paths: [grey_add_alot_of_things/grey_usu/common/company_types/zMoG_USU_MUC_rail_company_updates.txt]
---
# company_GN_railway

Вид компании · `company_GN_railway` · `common/company_types/zMoG_USU_MUC_rail_company_updates.txt:3254`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/greatnorthernrailway.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MINNESOTA`
- **possible_prestige_goods**: пусто
- **building_types**: [[grey_usu/Здания/Железнодорожный терминал|Железнодорожный терминал]], [[grey_usu/Здания/Железная дорога|Железная дорога]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 3277–3284
- **attainable**: скрипт, строки 3286–3296
- **possible**: скрипт, строки 3298–3313
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-iron-mine-throughput-add|building_iron_mine_throughput_add]] = `0.05` → [[vanilla/Здания/Железные рудники|Железные рудники]]
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.03`
- **ai_will_do**: скрипт, строки 3322–3329
- **ai_construction_targets**: скрипт, строки 3331–3338
- **ai_weight**: скрипт, строки 3339–3341
