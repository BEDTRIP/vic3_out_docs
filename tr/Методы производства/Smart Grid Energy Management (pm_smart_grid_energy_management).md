---
type: concept
description: "Метод производства «Smart Grid Energy Management (pm_smart_grid_energy_management)» — T&R 1.13, `pm_smart_grid_energy_management`"
project: vic3
source: tr
aliases: ["Smart Grid Energy Management (pm_smart_grid_energy_management)", "Smart Grid Energy Management", "pm_smart_grid_energy_management"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smart_grid_energy_management
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Smart Grid Energy Management (pm_smart_grid_energy_management)

Метод производства · `pm_smart_grid_energy_management` · `common/production_methods/ztr_energy_production_methods.txt:1380`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_smart_grid_energy_management.dds`
- **unlocking_technologies**: [[tr/Технологии/Smart Energy Grid|Smart Energy Grid]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_telecommunications_add` = `2` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `-400` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_renewable_energy_power_plant)|Automation (pmg_automation_building_renewable_energy_power_plant)]]
