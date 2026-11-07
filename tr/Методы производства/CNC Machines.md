---
type: concept
description: "Метод производства «CNC Machines» — T&R 1.13, `pm_cnc_machines`"
project: vic3
source: tr
aliases: ["CNC Machines", "pm_cnc_machines"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cnc_machines
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# CNC Machines

Метод производства · `pm_cnc_machines` · `common/production_methods/ztr_new_production_methods.txt:4775`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_cnc_machines.dds`
- **unlocking_technologies**: [[tr/Технологии/CNC Control|CNC Control]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `45` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_rubber_add` = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_computer_add` = `10` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - `goods_output_robotics_add` = `90` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - `building_employment_academics_add` = `750` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_machinists_add` = `1750` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Robotics|Robotics]]
