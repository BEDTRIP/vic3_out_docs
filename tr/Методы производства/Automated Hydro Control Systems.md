---
type: concept
description: "Метод производства «Automated Hydro Control Systems» — T&R 1.13, `pm_automated_hydro_control_systems`"
project: vic3
source: tr
aliases: ["Automated Hydro Control Systems", "pm_automated_hydro_control_systems"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_automated_hydro_control_systems
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Automated Hydro Control Systems

Метод производства · `pm_automated_hydro_control_systems` · `common/production_methods/ztr_energy_production_methods.txt:293`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_automated_hydro_control_systems.dds`
- **unlocking_technologies**: [[tr/Технологии/Automated Industrial Robots|Automated Industrial Robots]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `4` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_lubricant_add` = `5` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_plastics_add` = `2` → [[tr/Товары/Пластмассы|Пластмассы]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `-2500` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Reservoir Dams (pm_reservoir_dams_2)|Reservoir Dams (pm_reservoir_dams_2)]], [[tr/Методы производства/Reservoir Dams (pm_reservoir_dams_3)|Reservoir Dams (pm_reservoir_dams_3)]], [[tr/Методы производства/Advanced Turbine Generators (pm_advanced_turbine_generators_2)|Advanced Turbine Generators (pm_advanced_turbine_generators_2)]], [[tr/Методы производства/Advanced Turbine Generators (pm_advanced_turbine_generators_3)|Advanced Turbine Generators (pm_advanced_turbine_generators_3)]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_hydroelectric_power_plant)|Automation (pmg_automation_building_hydroelectric_power_plant)]]
