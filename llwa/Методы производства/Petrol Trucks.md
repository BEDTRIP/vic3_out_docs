---
type: concept
description: "Метод производства «Petrol Trucks» — LLWA 1.13, `LLWA_pm_petrol_trucks`"
project: vic3
source: llwa
aliases: ["Petrol Trucks", "LLWA_pm_petrol_trucks"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_petrol_trucks
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Petrol Trucks

Метод производства · `LLWA_pm_petrol_trucks` · `common/production_methods/LLWA_roads.txt:116`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_petrol_trucks.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Двигатель внутреннего сгорания|Двигатель внутреннего сгорания]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_automobiles_add` = `4` → [[vanilla/Товары/Автомобили|Автомобили]]
    - `goods_input_oil_add` = `2` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_transportation_add` = `30` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `300` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_clerks_add` = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `25`
    - `state_pollution_generation_add` = `7`
    - `state_infrastructure_from_population_max_add` = `2`
    - `state_infrastructure_from_automobiles_consumption_add` = `0.20`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Electric Buses|Electric Buses]], [[llwa/Методы производства/Motorbuses|Motorbuses]], [[llwa/Методы производства/Steam Buses|Steam Buses]]
