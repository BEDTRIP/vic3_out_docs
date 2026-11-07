---
type: concept
description: "Метод производства «Advanced Assembly Lines (pm_advanced_assembly_lines_building_automotive_industry)» — T&R 1.13, `pm_advanced_assembly_lines_building_automotive_industry`"
project: vic3
source: tr
aliases: ["Advanced Assembly Lines (pm_advanced_assembly_lines_building_automotive_industry)", "Advanced Assembly Lines", "pm_advanced_assembly_lines_building_automotive_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_assembly_lines_building_automotive_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Assembly Lines (pm_advanced_assembly_lines_building_automotive_industry)

Метод производства · `pm_advanced_assembly_lines_building_automotive_industry` · `common/production_methods/ztr_new_production_methods.txt:886`

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
    - `building_employment_laborers_add` = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-1000` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Автоматизация (pmg_automation_building_automotive_industry)|Автоматизация (pmg_automation_building_automotive_industry)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Hybrid Vehicles|Hybrid Vehicles]], [[tr/Методы производства/Post-war Vehicles|Post-war Vehicles]], [[tr/Методы производства/Smart Vehicles|Smart Vehicles]], [[tr/Методы производства/Массовое производство|Массовое производство]]
