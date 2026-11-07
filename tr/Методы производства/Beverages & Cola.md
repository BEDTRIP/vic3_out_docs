---
type: concept
description: "Метод производства «Beverages & Cola» — T&R 1.13, `pm_beverages_cola`"
project: vic3
source: tr
aliases: ["Beverages & Cola", "pm_beverages_cola"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_beverages_cola
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Beverages & Cola

Метод производства · `pm_beverages_cola` · `common/production_methods/ztr_new_production_methods.txt:7243`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_beverages_cola.dds`
- **unlocking_technologies**: [[tr/Технологии/Fast Food|Fast Food]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `0.02`
- **unlocking_production_methods**: [[vanilla/Методы производства/Кондитерские|Кондитерские]], [[vanilla/Методы производства/Пекарный порошок|Пекарный порошок]], [[tr/Методы производства/Ultra-processed Food|Ultra-processed Food]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-sugar-add|goods_input_sugar_add]] = `55` → [[vanilla/Товары/Сахар|Сахар]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `15` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fruit-add|goods_input_fruit_add]] = `10` → [[vanilla/Товары/Фрукты|Фрукты]]
    - `goods_input_pharmaceuticals_add` = `5` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-liquor-add|goods_output_liquor_add]] = `80` → [[vanilla/Товары/Спирт|Спирт]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wine-add|goods_output_wine_add]] = `20` → [[vanilla/Товары/Вино|Вино]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coffee-add|goods_output_coffee_add]] = `20` → [[vanilla/Товары/Кофе|Кофе]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-tea-add|goods_output_tea_add]] = `20` → [[vanilla/Товары/Чай|Чай]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-groceries-add|goods_output_groceries_add]] = `-60` → [[vanilla/Товары/Продукты|Продукты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Перегонка|Перегонка]]
