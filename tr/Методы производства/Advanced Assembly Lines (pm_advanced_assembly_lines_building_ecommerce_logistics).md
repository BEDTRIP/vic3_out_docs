---
type: concept
description: "Метод производства «Advanced Assembly Lines (pm_advanced_assembly_lines_building_ecommerce_logistics)» — T&R 1.13, `pm_advanced_assembly_lines_building_ecommerce_logistics`"
project: vic3
source: tr
aliases: ["Advanced Assembly Lines (pm_advanced_assembly_lines_building_ecommerce_logistics)", "Advanced Assembly Lines", "pm_advanced_assembly_lines_building_ecommerce_logistics"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_assembly_lines_building_ecommerce_logistics
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Assembly Lines (pm_advanced_assembly_lines_building_ecommerce_logistics)

Метод производства · `pm_advanced_assembly_lines_building_ecommerce_logistics` · `common/production_methods/ztr_new_production_methods.txt:1052`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Mechanical Arms|Mechanical Arms]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lubricant_add` = `2` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_ecommerce_logistics)|Automation (pmg_automation_building_ecommerce_logistics)]]
