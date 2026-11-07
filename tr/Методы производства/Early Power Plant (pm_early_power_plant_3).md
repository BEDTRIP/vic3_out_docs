---
type: concept
description: "Метод производства «Early Power Plant (pm_early_power_plant_3)» — T&R 1.13, `pm_early_power_plant_3`"
project: vic3
audience: agent
source: tr
aliases: ["Early Power Plant (pm_early_power_plant_3)", "Early Power Plant", "pm_early_power_plant_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_early_power_plant_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Early Power Plant (pm_early_power_plant_3)

Метод производства · `pm_early_power_plant_3` · `common/production_methods/ztr_energy_production_methods.txt:834`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/power_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `25`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `1` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `4` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `4` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_copperwires_add` = `1` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `25` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Pressurized HDPE Systems (pm_pressurized_systems_power_plant)|Pressurized HDPE Systems (pm_pressurized_systems_power_plant)]], [[tr/Методы производства/Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)|Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)]]
