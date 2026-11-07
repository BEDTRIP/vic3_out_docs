---
type: concept
description: "Метод производства «Basic Electric Control (pm_basic_electric_control_building_general)» — T&R 1.13, `pm_basic_electric_control_building_general`"
project: vic3
audience: agent
source: tr
aliases: ["Basic Electric Control (pm_basic_electric_control_building_general)", "Basic Electric Control", "pm_basic_electric_control_building_general"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_electric_control_building_general
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Basic Electric Control (pm_basic_electric_control_building_general)

Метод производства · `pm_basic_electric_control_building_general` · `common/production_methods/ztr_new_production_methods.txt:57`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electroniccomponents.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Industrial Mechatronics|Industrial Mechatronics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electroniccomponents_add` = `3` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-350` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_general)|Automation (pmg_automation_building_general)]]
