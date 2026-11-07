---
type: concept
description: "Метод производства «Geothermal Turbine (pm_geothermal_turbine_2)» — T&R 1.13, `pm_geothermal_turbine_2`"
project: vic3
source: tr
aliases: ["Geothermal Turbine (pm_geothermal_turbine_2)", "Geothermal Turbine", "pm_geothermal_turbine_2"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_geothermal_turbine_2
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Geothermal Turbine (pm_geothermal_turbine_2)

Метод производства · `pm_geothermal_turbine_2` · `common/production_methods/ztr_energy_production_methods.txt:1170`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_geothermal_turbine.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[tr/Технологии/Geothermal Energy|Geothermal Energy]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copperwires_add` = `5` → [[tr/Товары/Wires|Wires]]
    - `goods_input_batteries_add` = `10` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `20` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `20` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `230` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `235` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `6250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `2000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/National Electricity System|National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Geothermal Reactor|Geothermal Reactor]]
