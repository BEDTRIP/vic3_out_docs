---
type: concept
description: "Метод производства «DUV Photolithography» — T&R 1.13, `pm_deep_uv_photolithography`"
project: vic3
source: tr
aliases: ["DUV Photolithography", "pm_deep_uv_photolithography"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_deep_uv_photolithography
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# DUV Photolithography

Метод производства · `pm_deep_uv_photolithography` · `common/production_methods/ztr_new_production_methods.txt:489`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_deep_uv_photolithography.dds`
- **unlocking_technologies**: [[tr/Технологии/Industrial Mechatronics|Industrial Mechatronics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_glass_add` = `5` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `-600` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_chip_foundry)|Automation (pmg_automation_building_chip_foundry)]]
