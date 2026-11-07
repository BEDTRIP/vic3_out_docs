---
type: concept
description: "Метод производства «Electric Fueled Pump (pm_electric_fueled_pump_building_copper_mine)» — T&R 1.13, `pm_electric_fueled_pump_building_copper_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Electric Fueled Pump (pm_electric_fueled_pump_building_copper_mine)", "Electric Fueled Pump", "pm_electric_fueled_pump_building_copper_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electric_fueled_pump_building_copper_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electric Fueled Pump (pm_electric_fueled_pump_building_copper_mine)

Метод производства · `pm_electric_fueled_pump_building_copper_mine` · `common/production_methods/ztr_new_production_methods.txt:2413`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/electric_fueled_pump.dds`
- **unlocking_technologies**: [[tr/Технологии/Thermal Cracking|Thermal Cracking]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_copper_add` = `105` → [[tr/Товары/Copper|Copper]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_copper_mine)|Mining Equipment (pmg_mining_equipment_building_copper_mine)]]
