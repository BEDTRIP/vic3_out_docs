---
type: concept
description: "Метод производства «pm_artisanal_cheese» — grey food 2 ranch 1.13, `pm_artisanal_cheese`"
project: vic3
source: grey_food_2_ranch
aliases: ["pm_artisanal_cheese"]
tags: [grey_food_2_ranch, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_artisanal_cheese
paths: [grey_add_alot_of_things/grey_food_2_ranch/common/production_methods/mog_4_cheese_pms.txt]
---
# pm_artisanal_cheese

Метод производства · `pm_artisanal_cheese` · `common/production_methods/mog_4_cheese_pms.txt:6`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/cheese.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `4` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `-15` → [[vanilla/Товары/Мясо|Мясо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-groceries-add|goods_output_groceries_add]] = `18` → [[vanilla/Товары/Продукты|Продукты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-100` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `50` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_food_2_ranch/Группы методов/pmg_dairy_products|pmg_dairy_products]]
