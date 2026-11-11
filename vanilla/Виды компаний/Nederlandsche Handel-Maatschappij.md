---
type: concept
description: "Вид компании «Nederlandsche Handel-Maatschappij» — ваниль 1.15, `company_nhm`"
project: vic3
audience: agent
source: vanilla
aliases: ["Nederlandsche Handel-Maatschappij", "company_nhm"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nhm
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Nederlandsche Handel-Maatschappij

Вид компании · `company_nhm` · `common/company_types/00_companies_ep2.txt:1099`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_nhm.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WEST_JAVA`
- **building_types**: [[vanilla/Здания/Кофейные плантации|Кофейные плантации]], [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]], [[vanilla/Здания/Плантации красильных растений|Плантации красильных растений]]
- **extension_building_types**: [[vanilla/Здания/Табачные плантации|Табачные плантации]], [[vanilla/Здания/Маковые плантации|Маковые плантации]], [[vanilla/Здания/Чайные плантации|Чайные плантации]]
- **possible_prestige_goods**: `prestige_good_java_coffee`
- **potential**: скрипт, строки 1123–1126
- **attainable**: скрипт, строки 1128–1136
- **possible**: скрипт, строки 1138–1165
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-mult|state_trade_capacity_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-laborers-mortality-mult|building_group_bg_plantations_laborers_mortality_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 1173–1177
- **ai_construction_targets**: скрипт, строки 1179–1198
- **ai_weight**: скрипт, строки 1200–1202
