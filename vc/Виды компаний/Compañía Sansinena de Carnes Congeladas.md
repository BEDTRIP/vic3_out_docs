---
type: concept
description: "Вид компании «Compañía Sansinena de Carnes Congeladas» — VC 1.15, `company_compania_sansinena_de_carnes_congeladas`"
project: vic3
audience: agent
source: vc
aliases: ["Compañía Sansinena de Carnes Congeladas", "company_compania_sansinena_de_carnes_congeladas"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_compania_sansinena_de_carnes_congeladas
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Compañía Sansinena de Carnes Congeladas]]"
---
# Compañía Sansinena de Carnes Congeladas

Вид компании · `company_compania_sansinena_de_carnes_congeladas` · `common/company_types/joi_companies.txt:7056`

## Отличия от ваниль

- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_compania_sansinena_de_carnes_congeladas.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BUENOS_AIRES`
- **building_types**: [[vc/Здания/Животноводческие фермы|Животноводческие фермы]], [[vc/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]], [[vc/Здания/Рыболовные верфи|Рыболовные верфи]]
- **possible_prestige_goods**: `prestige_good_river_plate_beef`
- **potential**: скрипт, строки 7078–7081
- **attainable**: скрипт, строки 7083–7091
- **possible**: скрипт, строки 7093–7110
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-mult|goods_output_meat_mult]] = `0.15` → [[vanilla/Товары/Мясо|Мясо]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-ranching-employee-mult|building_group_bg_ranching_employee_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 7118–7123
- **ai_construction_targets**: скрипт, строки 7125–7138
- **ai_weight**: скрипт, строки 7140–7142
