---
type: concept
description: "Метод производства «Advanced Electric Control (pm_advanced_electric_control_building_explosives_factory)» — T&R 1.13, `pm_advanced_electric_control_building_explosives_factory`"
project: vic3
source: tr
aliases: ["Advanced Electric Control (pm_advanced_electric_control_building_explosives_factory)", "Advanced Electric Control", "pm_advanced_electric_control_building_explosives_factory"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_electric_control_building_explosives_factory
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Electric Control (pm_advanced_electric_control_building_explosives_factory)

Метод производства · `pm_advanced_electric_control_building_explosives_factory` · `common/production_methods/ztr_new_production_methods.txt:7820`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_microprocessors.dds`
- **unlocking_technologies**: [[tr/Технологии/Embedded Control Systems|Embedded Control Systems]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_explosives_factory_automation)|Automation (pmg_explosives_factory_automation)]]
