---
type: concept
description: "Метод производства «EUV Photolithography» — T&R 1.13, `pm_euv_photolithography`"
project: vic3
audience: agent
source: tr
aliases: ["EUV Photolithography", "pm_euv_photolithography"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_euv_photolithography
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# EUV Photolithography

Метод производства · `pm_euv_photolithography` · `common/production_methods/ztr_new_production_methods.txt:512`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_euv_photolithography.dds`
- **unlocking_technologies**: [[tr/Технологии/EUV Photolithography|EUV Photolithography]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `5` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_commonores_add` = `2` → [[tr/Товары/Common Ores|Common Ores]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-900` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_chip_foundry)|Automation (pmg_automation_building_chip_foundry)]]
