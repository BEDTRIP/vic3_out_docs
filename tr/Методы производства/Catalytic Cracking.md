---
type: concept
description: "Метод производства «Catalytic Cracking» — T&R 1.13, `pm_catalytic_cracking`"
project: vic3
source: tr
aliases: ["Catalytic Cracking", "pm_catalytic_cracking"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_catalytic_cracking
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Catalytic Cracking

Метод производства · `pm_catalytic_cracking` · `common/production_methods/ztr_new_production_methods.txt:3605`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_catalytic_cracking.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Enhanced Cracking Distillation|Enhanced Cracking Distillation]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `25` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_advancedores_add` = `1` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `90` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_light_fuel_add` = `105` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_lubricant_add` = `30` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sulfur-add|goods_output_sulfur_add]] = `5` → [[vanilla/Товары/Сера|Сера]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/FuelOil production|FuelOil production]]
