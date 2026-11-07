---
type: concept
description: "Метод производства «Generative AI Models» — T&R 1.13, `pm_generative_ai_models`"
project: vic3
source: tr
aliases: ["Generative AI Models", "pm_generative_ai_models"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_generative_ai_models
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Generative AI Models

Метод производства · `pm_generative_ai_models` · `common/production_methods/ztr_data_production_methods.txt:618`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_generative_ai_models.dds`
- **unlocking_technologies**: [[tr/Технологии/Generative AI|Generative AI]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_organized_data_add` = `-90` → [[tr/Товары/Organized Data|Organized Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `20` → [[tr/Товары/Water|Water]]
    - `goods_output_ai_systems_add` = `35` → [[tr/Товары/AI Systems|AI Systems]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `125` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-125` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_production_methods**: [[tr/Методы производства/Distributed Computing Servers|Distributed Computing Servers]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/AI Service|AI Service]]
