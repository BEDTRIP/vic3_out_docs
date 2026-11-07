---
type: concept
description: "Метод производства «Arc-Welded Buildings» — E&F 1.13, `pm_arc_welded_buildings_private`"
project: vic3
source: ef
aliases: ["Arc-Welded Buildings", "pm_arc_welded_buildings_private"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_arc_welded_buildings_private
paths: [E&F/common/production_methods/14_ef_private_construction.txt]
---
# Arc-Welded Buildings

Метод производства · `pm_arc_welded_buildings_private` · `common/production_methods/14_ef_private_construction.txt:158`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/arc_welded_buildings.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Дуговая сварка|Дуговая сварка]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_construction_add` = `30`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_manufacture_stock_add` = `200` → [[ef/Товары/Manufacture Stock|Manufacture Stock]]
    - `goods_input_steel_add` = `12` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_glass_add` = `10` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_explosives_add` = `5` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_input_tools_add` = `8` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electricity_add` = `20` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `100` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `165` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_machinists_add` = `235` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_laborers_add` = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.1`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Private Construction Sector|Private Construction Sector]]
