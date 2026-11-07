---
type: concept
description: "Метод производства «pm_intensive_diet_control» — grey food 2 ranch 1.13, `pm_intensive_diet_control`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы B#^m-building-millet-farm-throughput-add|building_millet_farm_throughput_add]] = `0.01` → [[vanilla/Здания/Просяные поля|Просяные поля]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-mult|goods_output_grain_mult]] = `0.01` → [[vanilla/Товары/Зерно|Зерно]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-grain-add|goods_input_grain_add]] = `10` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fruit-add|goods_input_fruit_add]] = `6` → [[vanilla/Товары/Фрукты|Фрукты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `-9` → [[vanilla/Товары/Мясо|Мясо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `20` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silk-add|goods_output_silk_add]] = `8` → [[vanilla/Товары/Шёлк|Шёлк]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fertilizer-add|goods_output_fertilizer_add]] = `4` → [[vanilla/Товары/Удобрение|Удобрение]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/Производство шерсти|Производство шерсти]]
