---
type: concept
description: "Метод производства «Advanced Electric Control (pm_advanced_electric_control_building_renewable_energy_power_plant)» — T&R 1.13, `pm_advanced_electric_control_building_renewable_energy_power_plant`"
project: vic3
audience: agent
source: tr
aliases: ["Advanced Electric Control (pm_advanced_electric_control_building_renewable_energy_power_plant)", "Advanced Electric Control", "pm_advanced_electric_control_building_renewable_energy_power_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_electric_control_building_renewable_energy_power_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Advanced Electric Control (pm_advanced_electric_control_building_renewable_energy_power_plant)

Метод производства · `pm_advanced_electric_control_building_renewable_energy_power_plant` · `common/production_methods/ztr_energy_production_methods.txt:1359`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_microprocessors.dds`
- **unlocking_technologies**: [[tr/Технологии/Embedded Control Systems|Embedded Control Systems]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_telecommunications_add` = `2` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-200` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_renewable_energy_power_plant)|Automation (pmg_automation_building_renewable_energy_power_plant)]]
