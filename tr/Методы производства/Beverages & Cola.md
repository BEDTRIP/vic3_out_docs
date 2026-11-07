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
    - `state_mortality_mult` = `0.02`
- **unlocking_production_methods**: [[vanilla/Методы производства/Кондитерские|Кондитерские]], [[vanilla/Методы производства/Пекарный порошок|Пекарный порошок]], [[tr/Методы производства/Ultra-processed Food|Ultra-processed Food]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_sugar_add` = `55` → [[vanilla/Товары/Сахар|Сахар]]
    - `goods_input_glass_add` = `15` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_fruit_add` = `10` → [[vanilla/Товары/Фрукты|Фрукты]]
    - `goods_input_pharmaceuticals_add` = `5` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_output_liquor_add` = `80` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_output_wine_add` = `20` → [[vanilla/Товары/Вино|Вино]]
    - `goods_output_coffee_add` = `20` → [[vanilla/Товары/Кофе|Кофе]]
    - `goods_output_tea_add` = `20` → [[vanilla/Товары/Чай|Чай]]
    - `goods_output_groceries_add` = `-60` → [[vanilla/Товары/Продукты|Продукты]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Перегонка|Перегонка]]
