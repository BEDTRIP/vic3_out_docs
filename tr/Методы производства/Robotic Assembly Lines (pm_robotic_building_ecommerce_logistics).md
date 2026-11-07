---
type: concept
description: "Метод производства «Robotic Assembly Lines (pm_robotic_building_ecommerce_logistics)» — T&R 1.13, `pm_robotic_building_ecommerce_logistics`"
project: vic3
source: tr
aliases: ["Robotic Assembly Lines (pm_robotic_building_ecommerce_logistics)", "Robotic Assembly Lines", "pm_robotic_building_ecommerce_logistics"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_robotic_building_ecommerce_logistics
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Robotic Assembly Lines (pm_robotic_building_ecommerce_logistics)

Метод производства · `pm_robotic_building_ecommerce_logistics` · `common/production_methods/ztr_new_production_methods.txt:1960`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_mechatronics_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Automated Industrial Robots|Automated Industrial Robots]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_lubricant_add` = `2` → [[tr/Товары/Lubricants|Lubricants]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_ecommerce_logistics)|Automation (pmg_automation_building_ecommerce_logistics)]]
