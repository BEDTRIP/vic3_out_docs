---
type: concept
description: "Метод производства «Multi-Core Processor» — T&R 1.13, `pm_multi_core_processor`"
project: vic3
source: tr
aliases: ["Multi-Core Processor", "pm_multi_core_processor"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_multi_core_processor
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Multi-Core Processor

Метод производства · `pm_multi_core_processor` · `common/production_methods/ztr_new_production_methods.txt:4711`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_multi_core_processor.dds`
- **unlocking_technologies**: [[tr/Технологии/Parallel Computing Architectures|Parallel Computing Architectures]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_advancedores_add` = `20` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_rare_earths_add` = `10` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_input_electroniccomponents_add` = `30` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_output_processors_add` = `70` → [[tr/Товары/Processors|Processors]]
  - **level_scaled**:
    - `building_employment_academics_add` = `750` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_engineers_add` = `1150` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Processor|Processor]]
