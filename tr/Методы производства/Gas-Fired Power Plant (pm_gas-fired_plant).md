---
type: concept
description: "Метод производства «Gas-Fired Power Plant (pm_gas-fired_plant)» — T&R 1.13, `pm_gas-fired_plant`"
project: vic3
source: tr
aliases: ["Gas-Fired Power Plant (pm_gas-fired_plant)", "Gas-Fired Power Plant", "pm_gas-fired_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gas-fired_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Gas-Fired Power Plant (pm_gas-fired_plant)

Метод производства · `pm_gas-fired_plant` · `common/production_methods/ztr_energy_production_methods.txt:542`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gas_fired_plant.dds`
- **replacement_if_valid**: [[tr/Методы производства/Gas-Fired Power Plant (pm_gas-fired_plant_2)|Gas-Fired Power Plant (pm_gas-fired_plant_2)]]
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[tr/Технологии/Gas Turbine|Gas Turbine]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `2` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_gas_add` = `25` → [[tr/Товары/Natural Gas|Natural Gas]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `85` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `9` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `200` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Local Electricity Systems|Local Electricity Systems]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
