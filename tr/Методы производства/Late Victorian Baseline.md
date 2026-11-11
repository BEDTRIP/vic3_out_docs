---
type: concept
description: "Метод производства «Late Victorian Baseline» — T&R 1.13, `pm_prewar_base`"
project: vic3
audience: agent
source: tr
aliases: ["Late Victorian Baseline", "pm_prewar_base"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_prewar_base
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Late Victorian Baseline

Метод производства · `pm_prewar_base` · `common/production_methods/ztr_unique_buildings_production_methods.txt:7`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refining1.dds`
- **state_modifiers**: пусто
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wood-add|goods_output_wood_add]] = `200` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_output_water_add` = `200` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-iron-add|goods_output_iron_add]] = `200` → [[vanilla/Товары/Железо|Железо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coal-add|goods_output_coal_add]] = `200` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sulfur-add|goods_output_sulfur_add]] = `200` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_bauxite_add` = `200` → [[tr/Товары/Bauxite|Bauxite]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-lead-add|goods_output_lead_add]] = `200` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_output_copper_add` = `200` → [[tr/Товары/Медь|Медь]]
    - `goods_output_commonores_add` = `200` → [[tr/Товары/Common Ores|Common Ores]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-oil-add|goods_output_oil_add]] = `200` → [[vanilla/Товары/ГСМ|ГСМ]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `10000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Modern State Baseline|Modern State Baseline]]
