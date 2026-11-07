---
type: concept
description: "Вид компании ««J. & P. Coats»» — VC 1.13, `company_j_p_coats`"
project: vic3
source: vc
aliases: ["«J. & P. Coats»", "J. & P. Coats", "company_j_p_coats"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_j_p_coats
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«J. & P. Coats»]]"
---
# «J. & P. Coats»

Вид компании · `company_j_p_coats` · `common/company_types/joi_companies.txt:2043`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_construction_targets**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_jp_coats.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MIDLANDS`, `STATE_HOME_COUNTIES`
- **building_types**: [[vc/Здания/Текстильные фабрики|Текстильные фабрики]], [[vc/Здания/Плантации хлопка|Плантации хлопка]], [[vc/Здания/Плантации красильных растений|Плантации красильных растений]]
- **extension_building_types**: [[vc/Здания/Заводы синтетики|Заводы синтетики]]
- **possible_prestige_goods**: `prestige_good_british_trench_coats`
- **potential**: скрипт, строки 2065–2067
- **attainable**: скрипт, строки 2069–2075
- **possible**: скрипт, строки 2077–2097
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[vc/Здания/Текстильные фабрики|Текстильные фабрики]]
  - [[vanilla/движок/Модификаторы B#^m-building-cotton-plantation-throughput-add|building_cotton_plantation_throughput_add]] = `0.1` → [[vc/Здания/Плантации хлопка|Плантации хлопка]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-clothes-mult|goods_output_clothes_mult]] = `0.05` → [[vanilla/Товары/Одежда|Одежда]]
- **ai_will_do**: скрипт, строки 2105–2111
- **ai_construction_targets**: скрипт, строки 2113–2120
- **ai_weight**: скрипт, строки 2122–2124
