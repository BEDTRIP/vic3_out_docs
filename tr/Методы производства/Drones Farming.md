---
type: concept
description: "Метод производства «Drones Farming» — T&R 1.13, `pm_hydroponic_drones_farming`"
project: vic3
source: tr
aliases: ["Drones Farming", "pm_hydroponic_drones_farming"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hydroponic_drones_farming
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Drones Farming

Метод производства · `pm_hydroponic_drones_farming` · `common/production_methods/ztr_new_production_methods.txt:6673`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_drones_farming.dds`
- **unlocking_technologies**: [[tr/Технологии/Civil Drones|Civil Drones]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `-2` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `-2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `-1` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_telecommunications_add` = `1` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_robotics_add` = `4` → [[tr/Товары/Robotics|Robotics]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.25`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `-50` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_hydroponic_automation_drone)|Automation (pmg_hydroponic_automation_drone)]]
