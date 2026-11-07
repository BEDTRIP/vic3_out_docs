---
type: concept
description: "Метод производства «Celluloid Processing» — T&R 1.13, `pm_celluloid_processing`"
project: vic3
audience: agent
source: tr
aliases: ["Celluloid Processing", "pm_celluloid_processing"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_celluloid_processing
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Celluloid Processing

Метод производства · `pm_celluloid_processing` · `common/production_methods/ztr_new_production_methods.txt:3715`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_celluloid_processing.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Пластмассы|Пластмассы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-liquor-add|goods_input_liquor_add]] = `5` → [[vanilla/Товары/Спирт|Спирт]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `65` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_water_add` = `2` → [[tr/Товары/Water|Water]]
    - `goods_output_plastics_add` = `65` → [[tr/Товары/Пластмассы|Пластмассы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Plastics & Rubber production|Plastics & Rubber production]]
