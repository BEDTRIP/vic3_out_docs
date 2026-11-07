---
type: concept
description: "Метод производства «Advanced Assembly» — T&R 1.13, `pm_advanced_assembly_lines_building_consumer_electronics_industry`"
project: vic3
source: tr
aliases: ["Advanced Assembly", "pm_advanced_assembly_lines_building_consumer_electronics_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_assembly_lines_building_consumer_electronics_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Assembly

Метод производства · `pm_advanced_assembly_lines_building_consumer_electronics_industry` · `common/production_methods/ztr_new_production_methods.txt:946`

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
    - `building_employment_machinists_add` = `-1000` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_consumer_electronics_industry)|Automation (pmg_automation_building_consumer_electronics_industry)]]
