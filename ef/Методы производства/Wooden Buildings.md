---
type: concept
description: "Метод производства «Wooden Buildings» — E&F 1.13, `pm_wooden_buildings_private`"
project: vic3
audience: agent
source: ef
aliases: ["Wooden Buildings", "pm_wooden_buildings_private"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_wooden_buildings_private
paths: [E&F/common/production_methods/14_ef_private_construction.txt]
---
# Wooden Buildings

Метод производства · `pm_wooden_buildings_private` · `common/production_methods/14_ef_private_construction.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wooden_buildings.dds`
- **is_default**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-construction-add|country_construction_add]] = `2`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-manufacture-stock-add|goods_output_manufacture_stock_add]] = `50` → [[ef/Товары/Manufacture Stock|Manufacture Stock]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `5` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `20` → [[vanilla/Товары/Древесина|Древесина]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `50` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `125` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-laborers-mortality-mult|building_laborers_mortality_mult]] = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Private Construction Sector|Private Construction Sector]]
