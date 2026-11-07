---
type: concept
description: "Метод производства «Gas-Fired Power Plant (pm_gas-fired_plant_3)» — T&R 1.13, `pm_gas-fired_plant_3`"
project: vic3
source: tr
aliases: ["Gas-Fired Power Plant (pm_gas-fired_plant_3)", "Gas-Fired Power Plant", "pm_gas-fired_plant_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gas-fired_plant_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Gas-Fired Power Plant (pm_gas-fired_plant_3)

Метод производства · `pm_gas-fired_plant_3` · `common/production_methods/ztr_energy_production_methods.txt:954`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gas_fired_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[tr/Технологии/Gas Turbine|Gas Turbine]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `2` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_gas_add` = `25` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_output_electricity_add` = `0` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `90` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `200` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Pressurized HDPE Systems (pm_pressurized_systems_power_plant)|Pressurized HDPE Systems (pm_pressurized_systems_power_plant)]], [[tr/Методы производства/Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)|Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)]]
