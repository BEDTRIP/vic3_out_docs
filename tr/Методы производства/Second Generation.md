---
type: concept
description: "Метод производства «Second Generation» — T&R 1.13, `pm_nuclear_second_generation`"
project: vic3
source: tr
aliases: ["Second Generation", "pm_nuclear_second_generation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nuclear_second_generation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Second Generation

Метод производства · `pm_nuclear_second_generation` · `common/production_methods/ztr_energy_production_methods.txt:1047`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_nuclear_first_generation.dds`
- **unlocking_technologies**: [[tr/Технологии/Gen II Nuclear Reactor|Gen II Nuclear Reactor]]
- **unlocking_production_methods**: [[tr/Методы производства/Nuclear Fission Power Plant (pm_nuclear-fission_plant_3)|Nuclear Fission Power Plant (pm_nuclear-fission_plant_3)]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - `goods_output_electricity_add` = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `20` → [[tr/Товары/National Electricity|National Electricity]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Reactor Refining|Reactor Refining]]
