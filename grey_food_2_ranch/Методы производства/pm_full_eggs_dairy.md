---
type: concept
description: "Метод производства «pm_full_eggs_dairy» — grey food 2 ranch 1.13, `pm_full_eggs_dairy`"
project: vic3
source: grey_food_2_ranch
aliases: ["pm_full_eggs_dairy"]
tags: [grey_food_2_ranch, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_full_eggs_dairy
paths: [grey_add_alot_of_things/grey_food_2_ranch/common/production_methods/mog_4_cheese_pms.txt]
---
# pm_full_eggs_dairy

Метод производства · `pm_full_eggs_dairy` · `common/production_methods/mog_4_cheese_pms.txt:90`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/chicken_coop.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пастеризация|Пастеризация]]
- **unlocking_production_methods**: [[grey_food_2_ranch/Методы производства/pm_battery_farming|pm_battery_farming]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.02` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `10` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `-20` → [[vanilla/Товары/Мясо|Мясо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-groceries-add|goods_output_groceries_add]] = `44` → [[vanilla/Товары/Продукты|Продукты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `200` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/pmg_dairy_products|pmg_dairy_products]]
