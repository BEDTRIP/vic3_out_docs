---
type: concept
description: "Метод производства «Basic Electric Control (pm_basic_electric_control_building_synthetics_plant)» — T&R 1.13, `pm_basic_electric_control_building_synthetics_plant`"
project: vic3
source: tr
aliases: ["Basic Electric Control (pm_basic_electric_control_building_synthetics_plant)", "Basic Electric Control", "pm_basic_electric_control_building_synthetics_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_electric_control_building_synthetics_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Basic Electric Control (pm_basic_electric_control_building_synthetics_plant)

Метод производства · `pm_basic_electric_control_building_synthetics_plant` · `common/production_methods/ztr_new_production_methods.txt:7709`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electroniccomponents.dds`
- **unlocking_technologies**: [[tr/Технологии/Industrial Mechatronics|Industrial Mechatronics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_synthetics_plant)|Automation (pmg_automation_building_synthetics_plant)]]
