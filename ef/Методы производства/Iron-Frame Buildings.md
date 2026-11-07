---
type: concept
description: "Метод производства «Iron-Frame Buildings» — E&F 1.13, `pm_iron_frame_buildings_private`"
project: vic3
audience: agent
source: ef
aliases: ["Iron-Frame Buildings", "pm_iron_frame_buildings_private"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_iron_frame_buildings_private
paths: [E&F/common/production_methods/14_ef_private_construction.txt]
---
# Iron-Frame Buildings

Метод производства · `pm_iron_frame_buildings_private` · `common/production_methods/14_ef_private_construction.txt:58`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/iron_frame_buildings.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Городское планирование|Городское планирование]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-construction-add|country_construction_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-manufacture-stock-add|goods_output_manufacture_stock_add]] = `100` → [[ef/Товары/Manufacture Stock|Manufacture Stock]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `10` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `5` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-iron-add|goods_input_iron_add]] = `15` → [[vanilla/Товары/Железо|Железо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `75` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `150` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `150` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-laborers-mortality-mult|building_laborers_mortality_mult]] = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Private Construction Sector|Private Construction Sector]]
