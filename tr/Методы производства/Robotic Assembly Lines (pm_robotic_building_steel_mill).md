---
type: concept
description: "Метод производства «Robotic Assembly Lines (pm_robotic_building_steel_mill)» — T&R 1.13, `pm_robotic_building_steel_mill`"
project: vic3
audience: agent
source: tr
aliases: ["Robotic Assembly Lines (pm_robotic_building_steel_mill)", "Robotic Assembly Lines", "pm_robotic_building_steel_mill"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_robotic_building_steel_mill
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Robotic Assembly Lines (pm_robotic_building_steel_mill)

Метод производства · `pm_robotic_building_steel_mill` · `common/production_methods/ztr_new_production_methods.txt:1757`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_mechatronics_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Automated Industrial Robots|Automated Industrial Robots]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `1` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_lubricant_add` = `2` → [[tr/Товары/Lubricants|Lubricants]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Автоматизация (pmg_automation_building_steel_mill)|Автоматизация (pmg_automation_building_steel_mill)]]
