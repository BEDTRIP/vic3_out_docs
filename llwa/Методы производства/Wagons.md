---
type: concept
description: "Метод производства «Wagons» — LLWA 1.13, `LLWA_pm_horse_wagons`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы G#^m-goods-input-grain-add|goods_input_grain_add]] = `5` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `5` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `5` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `300` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `10`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `0.5`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.05`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Stagecoaches|Stagecoaches]]
