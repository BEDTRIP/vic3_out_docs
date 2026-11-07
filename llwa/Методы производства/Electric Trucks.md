---
type: concept
description: "Метод производства «Electric Trucks» — LLWA 1.13, `LLWA_pm_electric_trucks`"
project: vic3
source: llwa
aliases: ["Electric Trucks", "LLWA_pm_electric_trucks"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_electric_trucks
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Electric Trucks

Метод производства · `LLWA_pm_electric_trucks` · `common/production_methods/LLWA_roads.txt:84`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_electric_trucks.dds`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
- **unlocking_technologies**: [[vanilla/Технологии/Электрические конденсаторы|Электрические конденсаторы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `4` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `25` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `15`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `1.5`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Electric Buses|Electric Buses]], [[llwa/Методы производства/Motorbuses|Motorbuses]], [[llwa/Методы производства/Steam Buses|Steam Buses]]
