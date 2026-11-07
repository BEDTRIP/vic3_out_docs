---
type: concept
description: "Метод производства «pm_refrigerated_workspaces» — grey food 2 ranch 1.13, `pm_refrigerated_workspaces`"
project: vic3
source: grey_food_2_ranch
aliases: ["pm_refrigerated_workspaces"]
tags: [grey_food_2_ranch, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_workspaces
paths: [grey_add_alot_of_things/grey_food_2_ranch/common/production_methods/mog_2_tooling_pms.txt]
---
# pm_refrigerated_workspaces

Метод производства · `pm_refrigerated_workspaces` · `common/production_methods/mog_2_tooling_pms.txt:73`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rpr_fridge_cow.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Пастеризация|Пастеризация]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `8` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electricity_add` = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_meat_add` = `40` → [[vanilla/Товары/Мясо|Мясо]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_farmers_add` = `100` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/pmg_automation_ranch|pmg_automation_ranch]]
- **Методы производства** (unlocking_production_methods): [[grey_food_2_ranch/Методы производства/pm_industrial_preserves|pm_industrial_preserves]]
