---
type: concept
description: "Метод производства «Coal-Fired Power Plant (pm_coal-fired_plant_3)» — T&R 1.13, `pm_coal-fired_plant_3`"
project: vic3
source: tr
aliases: ["Coal-Fired Power Plant (pm_coal-fired_plant_3)", "Coal-Fired Power Plant", "pm_coal-fired_plant_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_coal-fired_plant_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Coal-Fired Power Plant (pm_coal-fired_plant_3)

Метод производства · `pm_coal-fired_plant_3` · `common/production_methods/ztr_energy_production_methods.txt:869`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/coal_fired_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[tr/Технологии/Паровая турбина|Паровая турбина]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `50`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `1` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `3` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `2` → [[tr/Товары/Water|Water]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `20` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `6` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `55` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `350` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `150` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]
- **disallowing_laws**: [[tr/Законы/Basic Enviroment Protection|Basic Enviroment Protection]], [[tr/Законы/Active Restoration|Active Restoration]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Pressurized HDPE Systems (pm_pressurized_systems_power_plant)|Pressurized HDPE Systems (pm_pressurized_systems_power_plant)]], [[tr/Методы производства/Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)|Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)]]
