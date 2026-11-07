---
type: concept
description: "Метод производства «Neural Models» — T&R 1.13, `pm_neural_model_training`"
project: vic3
audience: agent
source: tr
aliases: ["Neural Models", "pm_neural_model_training"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_neural_model_training
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Neural Models

Метод производства · `pm_neural_model_training` · `common/production_methods/ztr_data_production_methods.txt:596`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_neural_model_training.dds`
- **unlocking_technologies**: [[tr/Технологии/Machine Learning|Machine Learning]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_organized_data_add` = `-60` → [[tr/Товары/Organized Data|Organized Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_output_ai_systems_add` = `15` → [[tr/Товары/AI Systems|AI Systems]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `125` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-125` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/AI Service|AI Service]]
