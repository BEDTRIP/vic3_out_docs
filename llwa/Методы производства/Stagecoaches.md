---
type: concept
description: "Метод производства «Stagecoaches» — LLWA 1.13, `LLWA_pm_stagecoaches`"
project: vic3
source: llwa
aliases: ["Stagecoaches", "LLWA_pm_stagecoaches"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_stagecoaches
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Stagecoaches

Метод производства · `LLWA_pm_stagecoaches` · `common/production_methods/LLWA_roads.txt:171`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_stagecoaches.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Wagons|Wagons]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `2` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `2` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Passenger Buses|Passenger Buses]]
