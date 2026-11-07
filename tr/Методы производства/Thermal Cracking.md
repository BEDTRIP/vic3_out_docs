---
type: concept
description: "Метод производства «Thermal Cracking» — T&R 1.13, `pm_thermal_cracking`"
project: vic3
audience: agent
source: tr
aliases: ["Thermal Cracking", "pm_thermal_cracking"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_thermal_cracking
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Thermal Cracking

Метод производства · `pm_thermal_cracking` · `common/production_methods/ztr_new_production_methods.txt:3567`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_thermal_cracking.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Thermal Cracking|Thermal Cracking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `90` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_light_fuel_add` = `65` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_lubricant_add` = `25` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_output_heavy_fuel_add` = `10` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coal-add|goods_output_coal_add]] = `20` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sulfur-add|goods_output_sulfur_add]] = `5` → [[vanilla/Товары/Сера|Сера]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/FuelOil production|FuelOil production]]
