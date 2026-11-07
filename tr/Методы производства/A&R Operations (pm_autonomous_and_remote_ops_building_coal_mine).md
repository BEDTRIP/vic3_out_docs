---
type: concept
description: "Метод производства «A&R Operations (pm_autonomous_and_remote_ops_building_coal_mine)» — T&R 1.13, `pm_autonomous_and_remote_ops_building_coal_mine`"
project: vic3
source: tr
aliases: ["A&R Operations (pm_autonomous_and_remote_ops_building_coal_mine)", "A&R Operations", "pm_autonomous_and_remote_ops_building_coal_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_autonomous_and_remote_ops_building_coal_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# A&R Operations (pm_autonomous_and_remote_ops_building_coal_mine)

Метод производства · `pm_autonomous_and_remote_ops_building_coal_mine` · `common/production_methods/ztr_new_production_methods.txt:3381`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_autonomous_and_remote_ops_mining.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[tr/Технологии/Autonomous & Remote Ops Mining|Autonomous & Remote Ops Mining]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - `goods_input_robotics_add` = `12` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coal-add|goods_output_coal_add]] = `165` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_coal_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_coal_mine)]]
