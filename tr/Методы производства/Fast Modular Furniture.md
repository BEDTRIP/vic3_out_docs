---
type: concept
description: "Метод производства «Fast Modular Furniture» — T&R 1.13, `pm_fast_modular_furniture_systems`"
project: vic3
audience: agent
source: tr
aliases: ["Fast Modular Furniture", "pm_fast_modular_furniture_systems"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fast_modular_furniture_systems
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Fast Modular Furniture

Метод производства · `pm_fast_modular_furniture_systems` · `common/production_methods/ztr_new_production_methods.txt:8278`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_fast_modular_furniture_systems.dds`
- **unlocking_technologies**: [[tr/Технологии/Fast Modular Furniture|Fast Modular Furniture]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `10` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `30` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_plastics_add` = `25` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-furniture-add|goods_output_furniture_add]] = `130` → [[vanilla/Товары/Мебель|Мебель]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-luxury-furniture-add|goods_output_luxury_furniture_add]] = `15` → [[vanilla/Товары/Роскошная мебель|Роскошная мебель]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_furniture_manufactory)|Основа (pmg_base_building_furniture_manufactory)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Designers Collections|Designers Collections]], [[tr/Методы производства/Точные инструменты|Точные инструменты]]
