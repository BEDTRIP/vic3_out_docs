---
type: concept
description: "Метод производства «Synthetic Furniture Molding» — T&R 1.13, `pm_synthetic_furniture_molding`"
project: vic3
source: tr
aliases: ["Synthetic Furniture Molding", "pm_synthetic_furniture_molding"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_synthetic_furniture_molding
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Synthetic Furniture Molding

Метод производства · `pm_synthetic_furniture_molding` · `common/production_methods/ztr_new_production_methods.txt:8251`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_synthetic_furniture_molding.dds`
- **unlocking_technologies**: [[tr/Технологии/Ethylene|Ethylene]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fabric_add` = `10` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_wood_add` = `30` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_tools_add` = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_plastics_add` = `20` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_furniture_add` = `125` → [[vanilla/Товары/Мебель|Мебель]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_furniture_manufactory)|Основа (pmg_base_building_furniture_manufactory)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Designers Collections|Designers Collections]], [[tr/Методы производства/Точные инструменты|Точные инструменты]]
