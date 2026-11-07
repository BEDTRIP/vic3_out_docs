---
type: concept
description: "Метод производства «Advanced Turbine Generators (pm_advanced_turbine_generators_3)» — T&R 1.13, `pm_advanced_turbine_generators_3`"
project: vic3
source: tr
aliases: ["Advanced Turbine Generators (pm_advanced_turbine_generators_3)", "Advanced Turbine Generators", "pm_advanced_turbine_generators_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_turbine_generators_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Advanced Turbine Generators (pm_advanced_turbine_generators_3)

Метод производства · `pm_advanced_turbine_generators_3` · `common/production_methods/ztr_energy_production_methods.txt:239`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_turbine_generators.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[vanilla/Технологии/ГСМ-турбина|ГСМ-турбина]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `75` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `10` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `30` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_copperwires_add` = `10` → [[tr/Товары/Wires|Wires]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `42` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `430` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `3750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroelectric Power Plant|Hydroelectric Power Plant]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Automated Hydro Control Systems|Automated Hydro Control Systems]], [[tr/Методы производства/Smart Grid Energy Management (pm_smart_grid_hydro)|Smart Grid Energy Management (pm_smart_grid_hydro)]]
