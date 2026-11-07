---
type: concept
description: "Вид компании «Jakub Klein a spol» — VC 1.13, `company_jakub_klein`"
project: vic3
audience: agent
source: vc
aliases: ["Jakub Klein a spol", "company_jakub_klein"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_jakub_klein
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Jakub Klein a spol]]"
---
# Jakub Klein a spol

Вид компании · `company_jakub_klein` · `common/company_types/joi_companies.txt:5877`

## Отличия от ваниль

- **possible_prestige_goods**: добавлено
- **attainable**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: убрано
- **ai_construction_targets**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_jakub_klein.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Лесозаготовки|Лесозаготовки]], [[vc/Здания/Бумажные фабрики|Бумажные фабрики]]
- **extension_building_types**: [[vc/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_generic_paper`
- **potential**: скрипт, строки 5896–5898
- **attainable**: пусто
- **possible**: скрипт, строки 5903–5915
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-paper-mill-throughput-add|building_paper_mill_throughput_add]] = `0.1` → [[vc/Здания/Бумажные фабрики|Бумажные фабрики]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-paper-mult|goods_output_paper_mult]] = `0.15` → [[vanilla/Товары/Бумага|Бумага]]
- **ai_weight**: скрипт, строки 5923–5925
