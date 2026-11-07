---
type: concept
description: "Метод производства «Drone Last Mile Delivery» — T&R 1.13, `pm_drone_last_mile`"
project: vic3
source: tr
aliases: ["Drone Last Mile Delivery", "pm_drone_last_mile"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_drone_last_mile
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Drone Last Mile Delivery

Метод производства · `pm_drone_last_mile` · `common/production_methods/ztr_data_production_methods.txt:1044`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_drone_last_mile.dds`
- **unlocking_technologies**: [[tr/Технологии/Civil Drones|Civil Drones]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `1` → [[tr/Товары/Автомобили|Автомобили]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Light Store Pickup|Light Store Pickup]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_transport_building_ecommerce_logistics)|Transport (pmg_transport_building_ecommerce_logistics)]]
