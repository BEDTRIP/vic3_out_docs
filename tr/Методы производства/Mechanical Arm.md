---
type: concept
description: "Метод производства «Mechanical Arm» — T&R 1.13, `pm_mechanical_arm`"
project: vic3
source: tr
aliases: ["Mechanical Arm", "pm_mechanical_arm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mechanical_arm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Mechanical Arm

Метод производства · `pm_mechanical_arm` · `common/production_methods/ztr_new_production_methods.txt:4747`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_mechanical_arm.dds`
- **unlocking_technologies**: [[tr/Технологии/Mechanical Arms|Mechanical Arms]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `35` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_rubber_add` = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_output_robotics_add` = `60` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - `building_employment_academics_add` = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_machinists_add` = `1750` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Robotics|Robotics]]
