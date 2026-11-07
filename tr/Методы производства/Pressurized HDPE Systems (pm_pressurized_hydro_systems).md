---
type: concept
description: "Метод производства «Pressurized HDPE Systems (pm_pressurized_hydro_systems)» — T&R 1.13, `pm_pressurized_hydro_systems`"
project: vic3
source: tr
aliases: ["Pressurized HDPE Systems (pm_pressurized_hydro_systems)", "Pressurized HDPE Systems", "pm_pressurized_hydro_systems"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_pressurized_hydro_systems
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Pressurized HDPE Systems (pm_pressurized_hydro_systems)

Метод производства · `pm_pressurized_hydro_systems` · `common/production_methods/ztr_energy_production_methods.txt:273`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_pressurized_hdpe_systems.dds`
- **unlocking_technologies**: [[tr/Технологии/HDPE|HDPE]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_plastics_add` = `2` → [[tr/Товары/Пластмассы|Пластмассы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-1250` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_hydroelectric_power_plant)|Automation (pmg_automation_building_hydroelectric_power_plant)]]
