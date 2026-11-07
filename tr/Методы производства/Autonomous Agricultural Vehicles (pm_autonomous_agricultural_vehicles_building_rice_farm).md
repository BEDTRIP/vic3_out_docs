---
type: concept
description: "Метод производства «Autonomous Agricultural Vehicles (pm_autonomous_agricultural_vehicles_building_rice_farm)» — T&R 1.13, `pm_autonomous_agricultural_vehicles_building_rice_farm`"
project: vic3
audience: agent
source: tr
aliases: ["Autonomous Agricultural Vehicles (pm_autonomous_agricultural_vehicles_building_rice_farm)", "Autonomous Agricultural Vehicles", "pm_autonomous_agricultural_vehicles_building_rice_farm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_autonomous_agricultural_vehicles_building_rice_farm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Autonomous Agricultural Vehicles (pm_autonomous_agricultural_vehicles_building_rice_farm)

Метод производства · `pm_autonomous_agricultural_vehicles_building_rice_farm` · `common/production_methods/ztr_agriculture_production_methods.txt:29`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_autonomous_agricultural_vehicles.dds`
- **unlocking_technologies**: [[tr/Технологии/Precision Agriculture|Precision Agriculture]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `1` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_water_add` = `1` → [[tr/Товары/Water|Water]]
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_telecommunications_add` = `3` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-5000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `-1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Процесс сбора урожая (pmg_harvesting_process_building_rice_farm)|Процесс сбора урожая (pmg_harvesting_process_building_rice_farm)]]
