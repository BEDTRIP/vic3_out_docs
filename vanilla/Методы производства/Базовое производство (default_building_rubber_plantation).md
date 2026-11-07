---
type: concept
description: "Метод производства «Базовое производство (default_building_rubber_plantation)» — ваниль 1.13, `default_building_rubber_plantation`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_rubber_plantation)", "Базовое производство", "default_building_rubber_plantation"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_rubber_plantation
paths: [.vanillaVIC3/common/production_methods/09_misc_resource.txt]
---
# Базовое производство (default_building_rubber_plantation)

Метод производства · `default_building_rubber_plantation` · `common/production_methods/09_misc_resource.txt:199`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/plantation_production.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-rubber-add|goods_output_rubber_add]] = `20` → [[vanilla/Товары/Каучук|Каучук]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `6000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rubber_plantation)|Основа (pmg_base_building_rubber_plantation)]]
