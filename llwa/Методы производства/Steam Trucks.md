---
type: concept
description: "Метод производства «Steam Trucks» — LLWA 1.13, `LLWA_pm_steam_trucks`"
project: vic3
source: llwa
aliases: ["Steam Trucks", "LLWA_pm_steam_trucks"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_steam_trucks
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Steam Trucks

Метод производства · `LLWA_pm_steam_trucks` · `common/production_methods/LLWA_roads.txt:53`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_steam_trucks.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Молотильные машины|Молотильные машины]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `4` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `2` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `50` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `20`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `1.0`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Electric Buses|Electric Buses]], [[llwa/Методы производства/Motorbuses|Motorbuses]], [[llwa/Методы производства/Steam Buses|Steam Buses]]
