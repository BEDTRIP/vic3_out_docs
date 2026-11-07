---
type: concept
description: "Метод производства «Highways» — T&R 1.13, `pm_highways_building_railway`"
project: vic3
source: tr
aliases: ["Highways", "pm_highways_building_railway"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_highways_building_railway
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Highways

Метод производства · `pm_highways_building_railway` · `common/production_methods/ztr_new_production_methods.txt:8794`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_basic_highway.dds`
- **unlocking_technologies**: [[tr/Технологии/Highway Systems|Highway Systems]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.15`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_heavy_fuel_add` = `1` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `100` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Road Infrastructure|Road Infrastructure]]
