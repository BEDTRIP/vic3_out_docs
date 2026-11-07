---
type: concept
description: "Метод производства «Third Generation» — T&R 1.13, `pm_nuclear_third_generation`"
project: vic3
audience: agent
source: tr
aliases: ["Third Generation", "pm_nuclear_third_generation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nuclear_third_generation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Third Generation

Метод производства · `pm_nuclear_third_generation` · `common/production_methods/ztr_energy_production_methods.txt:1072`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_nuclear_second_generation.dds`
- **unlocking_technologies**: [[tr/Технологии/Gen III Nuclear Reactor|Gen III Nuclear Reactor]]
- **unlocking_production_methods**: [[tr/Методы производства/Nuclear Fission Power Plant (pm_nuclear-fission_plant_3)|Nuclear Fission Power Plant (pm_nuclear-fission_plant_3)]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_computer_add` = `3` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `1` → [[tr/Товары/Software|Software]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `35` → [[tr/Товары/National Electricity|National Electricity]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Reactor Refining|Reactor Refining]]
