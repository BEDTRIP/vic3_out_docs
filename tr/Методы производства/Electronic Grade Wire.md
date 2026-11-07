---
type: concept
description: "Метод производства «Electronic Grade Wire» — T&R 1.13, `pm_electronic_grade_wires`"
project: vic3
source: tr
aliases: ["Electronic Grade Wire", "pm_electronic_grade_wires"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electronic_grade_wires
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electronic Grade Wire

Метод производства · `pm_electronic_grade_wires` · `common/production_methods/ztr_new_production_methods.txt:4145`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electronic_grade_wires.dds`
- **unlocking_technologies**: [[tr/Технологии/Optic Fibers|Optic Fibers]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_production_methods**: [[tr/Методы производства/Assembly Lines (pm_assembly_lines_building_electronics_plant)|Assembly Lines (pm_assembly_lines_building_electronics_plant)]], [[tr/Методы производства/Surface Mount Technology|Surface Mount Technology]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `40` → [[tr/Товары/Copper|Copper]]
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_rubber_add` = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_glass_add` = `10` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_output_copperwires_add` = `110` → [[tr/Товары/Wires|Wires]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
- **ai_value**: `2000`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Wire|Wire]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Embedded Control Circuit|Embedded Control Circuit]]
