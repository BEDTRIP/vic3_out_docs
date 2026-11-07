---
type: concept
description: "Метод производства «Hand Carts» — LLWA 1.13, `LLWA_pm_hand_carts`"
project: vic3
source: llwa
aliases: ["Hand Carts", "LLWA_pm_hand_carts"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_hand_carts
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Hand Carts

Метод производства · `LLWA_pm_hand_carts` · `common/production_methods/LLWA_roads.txt:29`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_hand_carts.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_wood_add` = `5` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_fabric_add` = `5` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_output_transportation_add` = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_shopkeepers_add` = `200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `10`
    - `state_infrastructure_from_population_max_add` = `0.5`
    - `state_infrastructure_from_automobiles_consumption_add` = `0.05`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Rickshaws|Rickshaws]]
