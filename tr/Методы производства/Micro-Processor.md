---
type: concept
description: "Метод производства «Micro-Processor» — T&R 1.13, `pm_microprocessor`"
project: vic3
source: tr
aliases: ["Micro-Processor", "pm_microprocessor"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_microprocessor
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Micro-Processor

Метод производства · `pm_microprocessor` · `common/production_methods/ztr_new_production_methods.txt:4677`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/microprocessors.dds`
- **unlocking_technologies**: [[tr/Технологии/Micro-Processor|Micro-Processor]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_advancedores_add` = `15` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_rare_earths_add` = `5` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_input_electroniccomponents_add` = `25` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_output_processors_add` = `55` → [[tr/Товары/Processors|Processors]]
  - **level_scaled**:
    - `building_employment_academics_add` = `600` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_engineers_add` = `1300` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Processor|Processor]]
