---
type: concept
description: "Метод производства «Surface Mount Technology» — T&R 1.13, `pm_surface_mount_technology_building_electronics_plant`"
project: vic3
source: tr
aliases: ["Surface Mount Technology", "pm_surface_mount_technology_building_electronics_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_surface_mount_technology_building_electronics_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Surface Mount Technology

Метод производства · `pm_surface_mount_technology_building_electronics_plant` · `common/production_methods/ztr_new_production_methods.txt:293`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/surface_mount_technology.dds`
- **unlocking_technologies**: [[tr/Технологии/CNC Control|CNC Control]]
- **unlocking_production_methods**: [[tr/Методы производства/Printed Circuit Board|Printed Circuit Board]], [[tr/Методы производства/Embedded Control Circuit|Embedded Control Circuit]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_robotics_add` = `8` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.1`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_electronics_plant)|Automation (pmg_automation_building_electronics_plant)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Electronic Grade Wire|Electronic Grade Wire]], [[tr/Методы производства/Embedded Control Circuit|Embedded Control Circuit]]
