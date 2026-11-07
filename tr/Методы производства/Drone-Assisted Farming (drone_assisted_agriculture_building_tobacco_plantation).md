---
type: concept
description: "Метод производства «Drone-Assisted Farming (drone_assisted_agriculture_building_tobacco_plantation)» — T&R 1.13, `drone_assisted_agriculture_building_tobacco_plantation`"
project: vic3
source: tr
aliases: ["Drone-Assisted Farming (drone_assisted_agriculture_building_tobacco_plantation)", "Drone-Assisted Farming", "drone_assisted_agriculture_building_tobacco_plantation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: drone_assisted_agriculture_building_tobacco_plantation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Drone-Assisted Farming (drone_assisted_agriculture_building_tobacco_plantation)

Метод производства · `drone_assisted_agriculture_building_tobacco_plantation` · `common/production_methods/ztr_agriculture_production_methods.txt:560`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_drones_farming_yellow.dds`
- **state_modifiers**: пусто
- **unlocking_technologies**: [[tr/Технологии/Civil Drones|Civil Drones]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `20` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_fertilizer_add` = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_telecommunications_add` = `8` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_electricity_add` = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_tobacco_add` = `105` → [[vanilla/Товары/Табак|Табак]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `3500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_tobacco_plantation)|Основа (pmg_base_building_tobacco_plantation)]]
