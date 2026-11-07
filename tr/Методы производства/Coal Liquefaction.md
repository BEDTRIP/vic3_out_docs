---
type: concept
description: "Метод производства «Coal Liquefaction» — T&R 1.13, `pm_mendelejew_coal_liquefaction`"
project: vic3
audience: agent
source: tr
aliases: ["Coal Liquefaction", "pm_mendelejew_coal_liquefaction"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mendelejew_coal_liquefaction
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Coal Liquefaction

Метод производства · `pm_mendelejew_coal_liquefaction` · `common/production_methods/ztr_modified_mr_production_methods.txt:3`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mendelejew_coal_liquefaction_pm.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Fuel|Synthetic Fuel]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `65` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_light_fuel_add` = `30` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_heavy_fuel_add` = `25` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/FuelOil production|FuelOil production]]
