---
type: concept
description: "Метод производства «Steel-Frame Buildings» — E&F 1.13, `pm_steel_frame_buildings_private`"
project: vic3
source: ef
aliases: ["Steel-Frame Buildings", "pm_steel_frame_buildings_private"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steel_frame_buildings_private
paths: [E&F/common/production_methods/14_ef_private_construction.txt]
---
# Steel-Frame Buildings

Метод производства · `pm_steel_frame_buildings_private` · `common/production_methods/14_ef_private_construction.txt:122`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steel_frame_buildings.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сооружения со стальными рамами|Сооружения со стальными рамами]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_construction_add` = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_manufacture_stock_add` = `150` → [[ef/Товары/Manufacture Stock|Manufacture Stock]]
    - `goods_input_steel_add` = `12` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_glass_add` = `10` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_explosives_add` = `2` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_input_tools_add` = `4` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `100` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `175` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_machinists_add` = `200` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_laborers_add` = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Private Construction Sector|Private Construction Sector]]
