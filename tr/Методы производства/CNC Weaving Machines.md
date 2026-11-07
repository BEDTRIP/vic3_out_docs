---
type: concept
description: "Метод производства «CNC Weaving Machines» — T&R 1.13, `pm_cnc_weaving_machines`"
project: vic3
audience: agent
source: tr
aliases: ["CNC Weaving Machines", "pm_cnc_weaving_machines"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cnc_weaving_machines
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# CNC Weaving Machines

Метод производства · `pm_cnc_weaving_machines` · `common/production_methods/ztr_new_production_methods.txt:675`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_cnc_weaving_machines.dds`
- **unlocking_technologies**: [[tr/Технологии/CNC Control|CNC Control]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Автоматизация (pmg_automation_building_textile_mill)|Автоматизация (pmg_automation_building_textile_mill)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Stretchwear|Stretchwear]], [[tr/Методы производства/Synthetic Fabrics|Synthetic Fabrics]]
