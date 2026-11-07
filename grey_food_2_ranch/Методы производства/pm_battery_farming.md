---
type: concept
description: "Метод производства «pm_battery_farming» — grey food 2 ranch 1.13, `pm_battery_farming`"
project: vic3
audience: agent
source: grey_food_2_ranch
aliases: ["pm_battery_farming"]
tags: [grey_food_2_ranch, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_battery_farming
paths: [grey_add_alot_of_things/grey_food_2_ranch/common/production_methods/mog_1_meat_pms.txt]
---
# pm_battery_farming

Метод производства · `pm_battery_farming` · `common/production_methods/mog_1_meat_pms.txt:42`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/m1_battery_farming.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Механизированное земледелие|Механизированное земледелие]]
- **unlocking_production_methods**: [[grey_food_2_ranch/Методы производства/Овцеводческие ранчо|Овцеводческие ранчо]], [[grey_food_2_ranch/Методы производства/Увеличенный сбор шерсти|Увеличенный сбор шерсти]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-grain-add|goods_input_grain_add]] = `20` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fruit-add|goods_input_fruit_add]] = `6` → [[vanilla/Товары/Фрукты|Фрукты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `60` → [[vanilla/Товары/Мясо|Мясо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fertilizer-add|goods_output_fertilizer_add]] = `4` → [[vanilla/Товары/Удобрение|Удобрение]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/Основа|Основа]]
- **Методы производства** (unlocking_production_methods): [[grey_food_2_ranch/Методы производства/pm_full_eggs_dairy|pm_full_eggs_dairy]], [[grey_food_2_ranch/Методы производства/pm_ranch_milk_production|pm_ranch_milk_production]], [[grey_food_2_ranch/Методы производства/Увеличенный сбор шерсти|Увеличенный сбор шерсти]]
