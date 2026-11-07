---
type: concept
description: "Метод производства «Embedded Control Circuit» — T&R 1.13, `pm_embedded_control_circuit`"
project: vic3
source: tr
aliases: ["Embedded Control Circuit", "pm_embedded_control_circuit"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_embedded_control_circuit
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Embedded Control Circuit

Метод производства · `pm_embedded_control_circuit` · `common/production_methods/ztr_new_production_methods.txt:4289`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/embedded_control_circuit.dds`
- **unlocking_technologies**: [[tr/Технологии/Embedded Control Systems|Embedded Control Systems]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_production_methods**: [[tr/Методы производства/Rubber Cabled Wire|Rubber Cabled Wire]], [[tr/Методы производства/PVC Cabled Wire|PVC Cabled Wire]], [[tr/Методы производства/Electronic Grade Wire|Electronic Grade Wire]], [[tr/Методы производства/Assembly Lines (pm_assembly_lines_building_electronics_plant)|Assembly Lines (pm_assembly_lines_building_electronics_plant)]], [[tr/Методы производства/Surface Mount Technology|Surface Mount Technology]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_advancedores_add` = `10` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_alloys_add` = `20` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_rare_earths_add` = `20` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_output_copperwires_add` = `-65` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electroniccomponents_add` = `120` → [[tr/Товары/Electronic Components|Electronic Components]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Electronic Components|Electronic Components]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Surface Mount Technology|Surface Mount Technology]]
