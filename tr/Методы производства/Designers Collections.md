---
type: concept
description: "Метод производства «Designers Collections» — T&R 1.13, `pm_designers_furniture_collections`"
project: vic3
source: tr
aliases: ["Designers Collections", "pm_designers_furniture_collections"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_designers_furniture_collections
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Designers Collections

Метод производства · `pm_designers_furniture_collections` · `common/production_methods/ztr_new_production_methods.txt:8306`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_designers_furniture_collections.dds`
- **unlocking_technologies**: [[tr/Технологии/Fast Modular Furniture|Fast Modular Furniture]]
- **unlocking_production_methods**: [[tr/Методы производства/Механизированные мастерские|Механизированные мастерские]], [[tr/Методы производства/Synthetic Furniture Molding|Synthetic Furniture Molding]], [[tr/Методы производства/Fast Modular Furniture|Fast Modular Furniture]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `-25` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-hardwood-add|goods_input_hardwood_add]] = `25` → [[vanilla/Товары/Твёрдая древесина|Твёрдая древесина]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-furniture-add|goods_output_furniture_add]] = `-60` → [[vanilla/Товары/Мебель|Мебель]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-luxury-furniture-add|goods_output_luxury_furniture_add]] = `65` → [[vanilla/Товары/Роскошная мебель|Роскошная мебель]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `750` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство предметов роскоши (pmg_luxury_building_furniture_manufactory)|Производство предметов роскоши (pmg_luxury_building_furniture_manufactory)]]
