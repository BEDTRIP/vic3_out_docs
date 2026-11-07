---
type: concept
description: "Метод производства «pm_intensive_diet_control» — grey food 2 ranch 1.13, `pm_intensive_diet_control`"
project: vic3
source: grey_food_2_ranch
aliases: ["pm_intensive_diet_control"]
tags: [grey_food_2_ranch, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_intensive_diet_control
paths: [grey_add_alot_of_things/grey_food_2_ranch/common/production_methods/mog_3_textile_pms.txt]
---
# pm_intensive_diet_control

Метод производства · `pm_intensive_diet_control` · `common/production_methods/mog_3_textile_pms.txt:63`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/sheep_control.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Улучшенное удобрение|Улучшенное удобрение]]
- **unlocking_production_methods**: [[grey_food_2_ranch/Методы производства/Интенсивный сбор шерсти|Интенсивный сбор шерсти]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_millet_farm_throughput_add` = `0.01` → [[vanilla/Здания/Просяные поля|Просяные поля]]
    - `goods_output_grain_mult` = `0.01` → [[vanilla/Товары/Зерно|Зерно]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_grain_add` = `10` → [[vanilla/Товары/Зерно|Зерно]]
    - `goods_input_fruit_add` = `6` → [[vanilla/Товары/Фрукты|Фрукты]]
    - `goods_output_meat_add` = `-9` → [[vanilla/Товары/Мясо|Мясо]]
    - `goods_output_fabric_add` = `20` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_output_silk_add` = `8` → [[vanilla/Товары/Шёлк|Шёлк]]
    - `goods_output_fertilizer_add` = `4` → [[vanilla/Товары/Удобрение|Удобрение]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/Производство шерсти|Производство шерсти]]
