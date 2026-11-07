---
type: concept
description: "Метод производства «Logistics Hubs» — T&R 1.13, `pm_logistics_hubs_building_railway`"
project: vic3
source: tr
aliases: ["Logistics Hubs", "pm_logistics_hubs_building_railway"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_logistics_hubs_building_railway
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Logistics Hubs

Метод производства · `pm_logistics_hubs_building_railway` · `common/production_methods/ztr_new_production_methods.txt:8857`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_logistics_hubs_building_railway.dds`
- **unlocking_technologies**: [[tr/Технологии/Freight Villages|Freight Villages]]
- **state_modifiers**:
  - **unscaled**:
    - `state_infrastructure_from_automobiles_consumption_add` = `0.3`
    - `state_trade_capacity_mult` = `0.1`
  - **level_scaled**:
    - `state_infrastructure_add` = `30`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_transportation_add` = `25` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_merchant_marine_add` = `1` → [[vanilla/Товары/Торговые корабли|Торговые корабли]]
    - `goods_input_electricity_add` = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_steel_add` = `7` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_heavy_fuel_add` = `2` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
    - `goods_input_robotics_add` = `1` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `100` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Road Infrastructure|Road Infrastructure]]
