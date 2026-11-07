---
type: concept
description: "Метод производства «Heavy Machineries (pm_heavy_machineries_building_bauxite_mine)» — T&R 1.13, `pm_heavy_machineries_building_bauxite_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Heavy Machineries (pm_heavy_machineries_building_bauxite_mine)", "Heavy Machineries", "pm_heavy_machineries_building_bauxite_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_heavy_machineries_building_bauxite_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Heavy Machineries (pm_heavy_machineries_building_bauxite_mine)

Метод производства · `pm_heavy_machineries_building_bauxite_mine` · `common/production_methods/ztr_new_production_methods.txt:3048`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/advanced_mining_systems.dds`
- **unlocking_technologies**: [[tr/Технологии/Heavy Machinery|Heavy Machinery]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `3` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_robotics_add` = `7` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_bauxite_add` = `130` → [[tr/Товары/Bauxite|Bauxite]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_bauxite_mine)|Mining Equipment (pmg_mining_equipment_building_bauxite_mine)]]
