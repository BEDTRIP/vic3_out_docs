---
type: concept
description: "Метод производства «Smart Grid Energy Management (pm_smart_grid_hydro)» — T&R 1.13, `pm_smart_grid_hydro`"
project: vic3
source: tr
aliases: ["Smart Grid Energy Management (pm_smart_grid_hydro)", "Smart Grid Energy Management", "pm_smart_grid_hydro"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smart_grid_hydro
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Smart Grid Energy Management (pm_smart_grid_hydro)

Метод производства · `pm_smart_grid_hydro` · `common/production_methods/ztr_energy_production_methods.txt:322`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_smart_grid_hydro.dds`
- **unlocking_technologies**: [[tr/Технологии/Smart Energy Grid|Smart Energy Grid]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `8` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_plastics_add` = `2` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_telecommunications_add` = `25` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_ai_systems_add` = `4` → [[tr/Товары/AI Systems|AI Systems]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-3000` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Reservoir Dams (pm_reservoir_dams_2)|Reservoir Dams (pm_reservoir_dams_2)]], [[tr/Методы производства/Reservoir Dams (pm_reservoir_dams_3)|Reservoir Dams (pm_reservoir_dams_3)]], [[tr/Методы производства/Advanced Turbine Generators (pm_advanced_turbine_generators_2)|Advanced Turbine Generators (pm_advanced_turbine_generators_2)]], [[tr/Методы производства/Advanced Turbine Generators (pm_advanced_turbine_generators_3)|Advanced Turbine Generators (pm_advanced_turbine_generators_3)]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_hydroelectric_power_plant)|Automation (pmg_automation_building_hydroelectric_power_plant)]]
