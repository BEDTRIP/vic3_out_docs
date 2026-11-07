---
type: concept
description: "Метод производства «Transistor» — T&R 1.13, `pm_transistor`"
project: vic3
source: tr
aliases: ["Transistor", "pm_transistor"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_transistor
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Transistor

Метод производства · `pm_transistor` · `common/production_methods/ztr_new_production_methods.txt:4226`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/transistor.dds`
- **unlocking_technologies**: [[tr/Технологии/Semiconductor Electronics|Semiconductor Electronics]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_alloys_add` = `30` → [[tr/Товары/Alloys|Alloys]]
    - `goods_output_copperwires_add` = `-30` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electroniccomponents_add` = `65` → [[tr/Товары/Electronic Components|Electronic Components]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Electronic Components|Electronic Components]]
