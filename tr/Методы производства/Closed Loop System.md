---
type: concept
description: "Метод производства «Closed Loop System» — T&R 1.13, `pm_automation_closed_loop_system`"
project: vic3
source: tr
aliases: ["Closed Loop System", "pm_automation_closed_loop_system"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_automation_closed_loop_system
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Closed Loop System

Метод производства · `pm_automation_closed_loop_system` · `common/production_methods/ztr_energy_production_methods.txt:1248`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_automation_closed_loop_system.dds`
- **unlocking_technologies**: [[tr/Технологии/HDPE|HDPE]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-3000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_geothermal_power_plant)|Automation (pmg_automation_building_geothermal_power_plant)]]
