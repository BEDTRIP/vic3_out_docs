---
type: concept
description: "Метод производства «Sailing Barges» — LLWA 1.13, `LLWA_pm_sailing_barges`"
project: vic3
source: llwa
aliases: ["Sailing Barges", "LLWA_pm_sailing_barges"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_sailing_barges
paths: [llwa/common/production_methods/LLWA_water.txt]
---
# Sailing Barges

Метод производства · `LLWA_pm_sailing_barges` · `common/production_methods/LLWA_water.txt:2`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_sailing_barges.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `10` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `5` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `20`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_water_base)|Основа (LLWA_pmg_water_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Riverboats|Riverboats]]
