---
type: concept
description: "Метод производства «Advanced Assembly Lines (pm_advanced_assembly_lines_building_paper_mill)» — T&R 1.13, `pm_advanced_assembly_lines_building_paper_mill`"
project: vic3
source: tr
aliases: ["Advanced Assembly Lines (pm_advanced_assembly_lines_building_paper_mill)", "Advanced Assembly Lines", "pm_advanced_assembly_lines_building_paper_mill"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_assembly_lines_building_paper_mill
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Assembly Lines (pm_advanced_assembly_lines_building_paper_mill)

Метод производства · `pm_advanced_assembly_lines_building_paper_mill` · `common/production_methods/ztr_new_production_methods.txt:1076`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Mechanical Arms|Mechanical Arms]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `3` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lubricant_add` = `3` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Автоматизация (pmg_automation_building_paper_mill)|Автоматизация (pmg_automation_building_paper_mill)]]
