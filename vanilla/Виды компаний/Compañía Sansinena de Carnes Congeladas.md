---
type: concept
description: "Вид компании «Compañía Sansinena de Carnes Congeladas» — ваниль 1.13, `company_compania_sansinena_de_carnes_congeladas`"
project: vic3
audience: agent
source: vanilla
aliases: ["Compañía Sansinena de Carnes Congeladas", "company_compania_sansinena_de_carnes_congeladas"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_compania_sansinena_de_carnes_congeladas
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Compañía Sansinena de Carnes Congeladas

Вид компании · `company_compania_sansinena_de_carnes_congeladas` · `common/company_types/00_companies_mp1.txt:76`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_compania_sansinena_de_carnes_congeladas.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BUENOS_AIRES`
- **building_types**: [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]]
- **possible_prestige_goods**: `prestige_good_river_plate_beef`
- **potential**: скрипт, строки 97–100
- **attainable**: скрипт, строки 102–110
- **possible**: скрипт, строки 112–129
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-port-throughput-add|building_port_throughput_add]] = `0.1` → [[vanilla/Здания/Порты|Порты]]
- **ai_will_do**: скрипт, строки 136–141
- **ai_construction_targets**: скрипт, строки 143–156
- **ai_weight**: скрипт, строки 158–160
