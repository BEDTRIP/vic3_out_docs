---
type: concept
description: "Вид компании «Guthrie & Co» — ваниль 1.15, `company_guthrie`"
project: vic3
audience: agent
source: vanilla
aliases: ["Guthrie & Co", "company_guthrie"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_guthrie
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Guthrie & Co

Вид компании · `company_guthrie` · `common/company_types/00_companies_ep2.txt:290`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_guthrie.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MALAYA`
- **building_types**: [[vanilla/Здания/Кофейные плантации|Кофейные плантации]], [[vanilla/Здания/Чайные плантации|Чайные плантации]]
- **extension_building_types**: [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 315–317
- **attainable**: скрипт, строки 319–327
- **possible**: скрипт, строки 329–342
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-port-throughput-add|building_port_throughput_add]] = `0.05` → [[vanilla/Здания/Порты|Порты]]
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-colony-growth-speed-mult|state_colony_growth_speed_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 350–355
- **ai_construction_targets**: скрипт, строки 357–370
- **ai_weight**: скрипт, строки 372–374
