---
type: concept
description: "Метод производства «Wagons» — LLWA 1.13, `LLWA_pm_horse_wagons`"
project: vic3
source: llwa
aliases: ["Wagons", "LLWA_pm_horse_wagons"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_horse_wagons
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Wagons

Метод производства · `LLWA_pm_horse_wagons` · `common/production_methods/LLWA_roads.txt:2`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_wagons.dds`
- **is_default**: `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_grain_add` = `5` → [[vanilla/Товары/Зерно|Зерно]]
    - `goods_input_wood_add` = `5` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_fabric_add` = `5` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_output_transportation_add` = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `300` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - `building_employment_shopkeepers_add` = `200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `10`
    - `state_infrastructure_from_population_max_add` = `0.5`
    - `state_infrastructure_from_automobiles_consumption_add` = `0.05`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Stagecoaches|Stagecoaches]]
