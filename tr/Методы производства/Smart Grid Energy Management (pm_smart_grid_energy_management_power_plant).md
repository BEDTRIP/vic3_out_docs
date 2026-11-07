---
type: concept
description: "Метод производства «Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)» — T&R 1.13, `pm_smart_grid_energy_management_power_plant`"
project: vic3
audience: agent
source: tr
aliases: ["Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)", "Smart Grid Energy Management", "pm_smart_grid_energy_management_power_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smart_grid_energy_management_power_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)

Метод производства · `pm_smart_grid_energy_management_power_plant` · `common/production_methods/ztr_energy_production_methods.txt:385`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_smart_grid_energy_management.dds`
- **unlocking_technologies**: [[tr/Технологии/Smart Energy Grid|Smart Energy Grid]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `1` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_plastics_add` = `1` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_telecommunications_add` = `3` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_ai_systems_add` = `1` → [[tr/Товары/AI Systems|AI Systems]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-100` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-50` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_production_methods**: [[tr/Методы производства/Early Power Plant (pm_early_power_plant_3)|Early Power Plant (pm_early_power_plant_3)]], [[tr/Методы производства/Coal-Fired Power Plant (pm_coal-fired_plant_3)|Coal-Fired Power Plant (pm_coal-fired_plant_3)]], [[tr/Методы производства/Oil-Fired Power Plant (pm_oil-fired_plant_3)|Oil-Fired Power Plant (pm_oil-fired_plant_3)]], [[tr/Методы производства/Gas-Fired Power Plant (pm_gas-fired_plant_3)|Gas-Fired Power Plant (pm_gas-fired_plant_3)]], [[tr/Методы производства/Nuclear Fission Power Plant (pm_nuclear-fission_plant_3)|Nuclear Fission Power Plant (pm_nuclear-fission_plant_3)]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_power_plant)|Automation (pmg_automation_building_power_plant)]]
