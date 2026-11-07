---
type: concept
description: "Метод производства «Advanced Electric Control (pm_advanced_electric_control_building_general)» — T&R 1.13, `pm_advanced_electric_control_building_general`"
project: vic3
source: tr
aliases: ["Advanced Electric Control (pm_advanced_electric_control_building_general)", "Advanced Electric Control", "pm_advanced_electric_control_building_general"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_electric_control_building_general
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Electric Control (pm_advanced_electric_control_building_general)

Метод производства · `pm_advanced_electric_control_building_general` · `common/production_methods/ztr_new_production_methods.txt:86`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_microprocessors.dds`
- **unlocking_technologies**: [[tr/Технологии/Embedded Control Systems|Embedded Control Systems]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - `goods_input_electricity_add` = `2` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `-150` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_general)|Automation (pmg_automation_building_general)]]
