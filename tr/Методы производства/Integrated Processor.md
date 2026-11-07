---
type: concept
description: "Метод производства «Integrated Processor» — T&R 1.13, `pm_integrated_circuit`"
project: vic3
source: tr
aliases: ["Integrated Processor", "pm_integrated_circuit"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_integrated_circuit
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Integrated Processor

Метод производства · `pm_integrated_circuit` · `common/production_methods/ztr_new_production_methods.txt:4643`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/processors.dds`
- **unlocking_technologies**: [[tr/Технологии/Integrated Circuits|Integrated Circuits]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_advancedores_add` = `10` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_electroniccomponents_add` = `15` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_output_processors_add` = `35` → [[tr/Товары/Processors|Processors]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Processor|Processor]]
