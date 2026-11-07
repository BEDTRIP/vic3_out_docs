---
type: concept
description: "Метод производства «Reservoir Dams (pm_reservoir_dams_2)» — T&R 1.13, `pm_reservoir_dams_2`"
project: vic3
audience: agent
source: tr
aliases: ["Reservoir Dams (pm_reservoir_dams_2)", "Reservoir Dams", "pm_reservoir_dams_2"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_reservoir_dams_2
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Reservoir Dams (pm_reservoir_dams_2)

Метод производства · `pm_reservoir_dams_2` · `common/production_methods/ztr_energy_production_methods.txt:121`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hydroelectric_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[vanilla/Технологии/Пневматические инструменты|Пневматические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `50` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `10` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `20` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_copperwires_add` = `10` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `170` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `175` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `3750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/National Electricity System|National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroelectric Power Plant|Hydroelectric Power Plant]]
- **Методы производства** (replacement_if_valid): [[tr/Методы производства/Reservoir Dams (pm_reservoir_dams)|Reservoir Dams (pm_reservoir_dams)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Automated Hydro Control Systems|Automated Hydro Control Systems]], [[tr/Методы производства/Smart Grid Energy Management (pm_smart_grid_hydro)|Smart Grid Energy Management (pm_smart_grid_hydro)]]
