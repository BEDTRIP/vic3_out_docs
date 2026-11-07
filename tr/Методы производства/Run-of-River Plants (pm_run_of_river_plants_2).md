---
type: concept
description: "Метод производства «Run-of-River Plants (pm_run_of_river_plants_2)» — T&R 1.13, `pm_run_of_river_plants_2`"
project: vic3
source: tr
aliases: ["Run-of-River Plants (pm_run_of_river_plants_2)", "Run-of-River Plants", "pm_run_of_river_plants_2"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_run_of_river_plants_2
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Run-of-River Plants (pm_run_of_river_plants_2)

Метод производства · `pm_run_of_river_plants_2` · `common/production_methods/ztr_energy_production_methods.txt:94`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_run_of_river_plants.dds`
- **is_hidden_when_unavailable**: `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `5` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `20` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_copperwires_add` = `5` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `85` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `90` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/National Electricity System|National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroelectric Power Plant|Hydroelectric Power Plant]]
- **Методы производства** (replacement_if_valid): [[tr/Методы производства/Run-of-River Plants (pm_run_of_river_plants)|Run-of-River Plants (pm_run_of_river_plants)]]
