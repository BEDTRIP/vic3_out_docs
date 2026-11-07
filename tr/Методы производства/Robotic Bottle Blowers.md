---
type: concept
description: "Метод производства «Robotic Bottle Blowers» — T&R 1.13, `pm_advanced_automatic_bottle_blowers`"
project: vic3
source: tr
aliases: ["Robotic Bottle Blowers", "pm_advanced_automatic_bottle_blowers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_automatic_bottle_blowers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Robotic Bottle Blowers

Метод производства · `pm_advanced_automatic_bottle_blowers` · `common/production_methods/ztr_new_production_methods.txt:213`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_automatic_bottle_blowers.dds`
- **unlocking_technologies**: [[tr/Технологии/Mechanical Arms|Mechanical Arms]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_gas_add` = `5` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_lubricant_add` = `2` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-1000` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Выдувание стекла|Выдувание стекла]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Houseware Moplen|Houseware Moplen]]
