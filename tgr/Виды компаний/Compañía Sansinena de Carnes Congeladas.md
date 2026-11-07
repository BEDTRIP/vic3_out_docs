---
type: concept
description: "Вид компании «Compañía Sansinena de Carnes Congeladas» — TGR 1.13, `company_compania_sansinena_de_carnes_congeladas`"
project: vic3
source: tgr
aliases: ["Compañía Sansinena de Carnes Congeladas", "company_compania_sansinena_de_carnes_congeladas"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_compania_sansinena_de_carnes_congeladas
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/Compañía Sansinena de Carnes Congeladas]]"
---
# Compañía Sansinena de Carnes Congeladas

Вид компании · `company_compania_sansinena_de_carnes_congeladas` · `common/company_types/TGR_TRADE_companies.txt:1245`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **potential**: изменено
- **attainable**: изменено
- **possible**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_compania_sansinena_de_carnes_congeladas.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BUENOS_AIRES`
- **building_types**: [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **potential**: скрипт, строки 1262–1264
- **possible_prestige_goods**: `prestige_good_river_plate_beef`
- **attainable**: пусто
- **possible**: скрипт, строки 1273–1282
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-port-throughput-add|building_port_throughput_add]] = `0.1` → [[vanilla/Здания/Порты|Порты]]
- **ai_will_do**: скрипт, строки 1289–1294
- **ai_construction_targets**: скрипт, строки 1296–1303
- **ai_weight**: скрипт, строки 1305–1307
