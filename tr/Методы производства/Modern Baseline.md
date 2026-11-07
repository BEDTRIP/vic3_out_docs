---
type: concept
description: "Метод производства «Modern Baseline» — T&R 1.13, `pm_advanced_base`"
project: vic3
source: tr
aliases: ["Modern Baseline", "pm_advanced_base"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_base
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Modern Baseline

Метод производства · `pm_advanced_base` · `common/production_methods/ztr_unique_buildings_production_methods.txt:73`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refining3.dds`
- **unlocking_technologies**: [[tr/Технологии/Neoliberalism|Neoliberalism]]
- **state_modifiers**: пусто
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wood-add|goods_output_wood_add]] = `400` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_output_water_add` = `400` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-iron-add|goods_output_iron_add]] = `400` → [[vanilla/Товары/Железо|Железо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coal-add|goods_output_coal_add]] = `400` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sulfur-add|goods_output_sulfur_add]] = `400` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_bauxite_add` = `400` → [[tr/Товары/Bauxite|Bauxite]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-lead-add|goods_output_lead_add]] = `400` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_output_copper_add` = `400` → [[tr/Товары/Copper|Copper]]
    - `goods_output_commonores_add` = `400` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_output_advancedores_add` = `400` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_output_rare_earths_add` = `400` → [[tr/Товары/Rare Earths|Rare Earths]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-tools-add|goods_output_tools_add]] = `400` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-paper-add|goods_output_paper_add]] = `400` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_light_fuel_add` = `400` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-oil-add|goods_output_oil_add]] = `400` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_gas_add` = `400` → [[tr/Товары/Natural Gas|Natural Gas]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `10000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Modern State Baseline|Modern State Baseline]]
