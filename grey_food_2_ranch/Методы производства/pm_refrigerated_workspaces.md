---
type: concept
description: "Метод производства «pm_refrigerated_workspaces» — grey food 2 ranch 1.13, `pm_refrigerated_workspaces`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Пастеризация|Пастеризация]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `8` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `40` → [[vanilla/Товары/Мясо|Мясо]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `100` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/pmg_automation_ranch|pmg_automation_ranch]]
- **Методы производства** (unlocking_production_methods): [[grey_food_2_ranch/Методы производства/pm_industrial_preserves|pm_industrial_preserves]]
