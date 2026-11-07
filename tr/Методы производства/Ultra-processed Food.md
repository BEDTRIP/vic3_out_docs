---
type: concept
description: "Метод производства «Ultra-processed Food» — T&R 1.13, `pm_ultraprocessed_snacks`"
project: vic3
audience: agent
source: tr
aliases: ["Ultra-processed Food", "pm_ultraprocessed_snacks"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_ultraprocessed_snacks
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Ultra-processed Food

Метод производства · `pm_ultraprocessed_snacks` · `common/production_methods/ztr_new_production_methods.txt:7315`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_ultraprocessed_snacks.dds`
- **unlocking_technologies**: [[tr/Технологии/Fast Food|Fast Food]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `0.04`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-grain-add|goods_input_grain_add]] = `100` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-sugar-add|goods_input_sugar_add]] = `70` → [[vanilla/Товары/Сахар|Сахар]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-groceries-add|goods_output_groceries_add]] = `200` → [[vanilla/Товары/Продукты|Продукты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_food_industry)|Основа (pmg_base_building_food_industry)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Beverages & Cola|Beverages & Cola]], [[tr/Методы производства/Gas Fired Ovens|Gas Fired Ovens]]
