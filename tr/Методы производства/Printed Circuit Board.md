---
type: concept
description: "Метод производства «Printed Circuit Board» — T&R 1.13, `pm_printed_circuit_board`"
project: vic3
audience: agent
source: tr
aliases: ["Printed Circuit Board", "pm_printed_circuit_board"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_printed_circuit_board
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Printed Circuit Board

Метод производства · `pm_printed_circuit_board` · `common/production_methods/ztr_new_production_methods.txt:4257`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/printed_circuit_board.dds`
- **unlocking_technologies**: [[tr/Технологии/Integrated Circuits|Integrated Circuits]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `25` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_alloys_add` = `25` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_copperwires_add` = `-50` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electroniccomponents_add` = `90` → [[tr/Товары/Electronic Components|Electronic Components]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Electronic Components|Electronic Components]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Surface Mount Technology|Surface Mount Technology]]
