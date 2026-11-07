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
    - `goods_input_engines_add` = `4` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_coal_add` = `2` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_transportation_add` = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `50` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_clerks_add` = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `20`
    - `state_pollution_generation_add` = `10`
    - `state_infrastructure_from_population_max_add` = `1.0`
    - `state_infrastructure_from_automobiles_consumption_add` = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Electric Buses|Electric Buses]], [[llwa/Методы производства/Motorbuses|Motorbuses]], [[llwa/Методы производства/Steam Buses|Steam Buses]]
