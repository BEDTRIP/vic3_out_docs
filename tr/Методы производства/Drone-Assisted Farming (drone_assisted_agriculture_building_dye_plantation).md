---
type: concept
description: "Метод производства «Drone-Assisted Farming (drone_assisted_agriculture_building_dye_plantation)» — T&R 1.13, `drone_assisted_agriculture_building_dye_plantation`"
project: vic3
source: tr
aliases: ["Drone-Assisted Farming (drone_assisted_agriculture_building_dye_plantation)", "Drone-Assisted Farming", "drone_assisted_agriculture_building_dye_plantation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: drone_assisted_agriculture_building_dye_plantation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Drone-Assisted Farming (drone_assisted_agriculture_building_dye_plantation)

Метод производства · `drone_assisted_agriculture_building_dye_plantation` · `common/production_methods/ztr_agriculture_production_methods.txt:648`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_drones_farming_yellow.dds`
- **state_modifiers**: пусто
- **unlocking_technologies**: [[tr/Технологии/Civil Drones|Civil Drones]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `3` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_telecommunications_add` = `2` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-dye-add|goods_output_dye_add]] = `105` → [[vanilla/Товары/Красители|Красители]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_dye_plantation)|Основа (pmg_base_building_dye_plantation)]]
