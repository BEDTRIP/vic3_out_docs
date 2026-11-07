---
type: concept
description: "Метод производства «AGI» — T&R 1.13, `pm_artificial_general_intelligence`"
project: vic3
source: tr
aliases: ["AGI", "pm_artificial_general_intelligence"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_artificial_general_intelligence
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# AGI

Метод производства · `pm_artificial_general_intelligence` · `common/production_methods/ztr_data_production_methods.txt:643`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_artificial_general_intelligence.dds`
- **unlocking_technologies**: [[tr/Технологии/AGI|AGI]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_organized_data_add` = `-250` → [[tr/Товары/Organized Data|Organized Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `40` → [[tr/Товары/Water|Water]]
    - `goods_output_ai_systems_add` = `80` → [[tr/Товары/AI Systems|AI Systems]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `125` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-125` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_production_methods**: [[tr/Методы производства/Distributed Computing Servers|Distributed Computing Servers]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/AI Service|AI Service]]
