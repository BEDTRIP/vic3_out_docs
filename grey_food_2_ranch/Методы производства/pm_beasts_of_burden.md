---
type: concept
description: "Метод производства «pm_beasts_of_burden» — grey food 2 ranch 1.13, `pm_beasts_of_burden`"
project: vic3
source: grey_food_2_ranch
aliases: ["pm_beasts_of_burden"]
tags: [grey_food_2_ranch, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_beasts_of_burden
paths: [grey_add_alot_of_things/grey_food_2_ranch/common/production_methods/mog_3_textile_pms.txt]
---
# pm_beasts_of_burden

Метод производства · `pm_beasts_of_burden` · `common/production_methods/mog_3_textile_pms.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/beasts_of_burden.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `2` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `1` → [[vanilla/Товары/Перевозка|Перевозка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `-1` → [[vanilla/Товары/Перевозка|Перевозка]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-millet-farm-throughput-add|building_millet_farm_throughput_add]] = `0.005` → [[vanilla/Здания/Просяные поля|Просяные поля]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-mult|goods_output_grain_mult]] = `0.005` → [[vanilla/Товары/Зерно|Зерно]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/Производство шерсти|Производство шерсти]]
