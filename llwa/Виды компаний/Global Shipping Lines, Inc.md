---
type: concept
description: "Вид компании «Global Shipping Lines, Inc» — LLWA 1.13, `LLWA_company_ship_line`"
project: vic3
source: llwa
aliases: ["Global Shipping Lines, Inc", "LLWA_company_ship_line"]
tags: [LLWA, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_company_ship_line
paths: [llwa/common/company_types/LLWA_companies.txt]
---
# Global Shipping Lines, Inc

Вид компании · `LLWA_company_ship_line` · `common/company_types/LLWA_companies.txt:101`

## Поля

- **icon**: `gfx/interface/icons/company_icons/LLWA_shipping_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **category**: `capitalist_owned`
- **flavored_company**: `no`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_corporation`
- **building_types**: [[llwa/Здания/Canal Waterway|Canal Waterway]], [[llwa/Здания/Natural Waterway|Natural Waterway]], [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[llwa/Здания/Железные дороги|Железные дороги]], [[llwa/Здания/Aerodrome|Aerodrome]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 131–133
- **attainable**:
  - `always` = `yes`
- **possible**: скрипт, строки 139–150
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-mult|state_trade_capacity_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 156–170
- **ai_construction_targets**: скрипт, строки 172–194
- **ai_weight**: скрипт, строки 196–198
