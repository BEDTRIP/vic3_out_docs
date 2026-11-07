---
type: concept
description: "Вид компании «company_IETT» — grey USU 1.13, `company_IETT`"
project: vic3
source: grey_usu
aliases: ["company_IETT"]
tags: [grey_usu, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_IETT
paths: [grey_add_alot_of_things/grey_usu/common/company_types/zMoG_USU_MUC_rail_company_updates.txt]
---
# company_IETT

Вид компании · `company_IETT` · `common/company_types/zMoG_USU_MUC_rail_company_updates.txt:2758`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/istanbul.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **possible_prestige_goods**: пусто
- **building_types**: [[grey_usu/Здания/Тепловая электростанция|Тепловая электростанция]], [[grey_usu/Здания/Железнодорожный терминал|Железнодорожный терминал]], [[grey_usu/Здания/Железная дорога|Железная дорога]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **potential**: скрипт, строки 2781–2783
- **attainable**: скрипт, строки 2785–2791
- **possible**: скрипт, строки 2793–2810
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.1` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 2818–2824
- **ai_construction_targets**: скрипт, строки 2826–2840
- **ai_weight**: скрипт, строки 2841–2843
