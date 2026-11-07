---
type: concept
description: "Метод производства «Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)» — T&R 1.13, `pm_advanced_assembly_lines_building_commonalloys_plant`"
project: vic3
source: tr
aliases: ["Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)", "Advanced Assembly Lines", "pm_advanced_assembly_lines_building_commonalloys_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_assembly_lines_building_commonalloys_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)

Метод производства · `pm_advanced_assembly_lines_building_commonalloys_plant` · `common/production_methods/ztr_new_production_methods.txt:759`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Mechanical Arms|Mechanical Arms]]
- **unlocking_production_methods**: [[tr/Методы производства/Advanced Alloys Techniques|Advanced Alloys Techniques]], [[tr/Методы производства/Alloys VAR|Alloys VAR]], [[tr/Методы производства/Hall-Héroult Process|Hall-Héroult Process]], [[tr/Методы производства/Electro-Refining Process|Electro-Refining Process]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lubricant_add` = `3` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_commonalloys_plant)|Automation (pmg_automation_building_commonalloys_plant)]]
