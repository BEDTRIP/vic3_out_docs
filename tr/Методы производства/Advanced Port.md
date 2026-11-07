---
type: concept
description: "Метод производства «Advanced Port» — T&R 1.13, `pm_advanced_port`"
project: vic3
source: tr
aliases: ["Advanced Port", "pm_advanced_port"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_port
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Port

Метод производства · `pm_advanced_port` · `common/production_methods/ztr_new_production_methods.txt:10225`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/modern_port.dds`
- **unlocking_technologies**: [[tr/Технологии/Advanced Harbor Facilities|Advanced Harbor Facilities]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steamers_add` = `5` → [[vanilla/Товары/Пароходы|Пароходы]]
    - `goods_input_robotics_add` = `1` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_heavy_fuel_add` = `4` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
    - `goods_output_merchant_marine_add` = `30` → [[vanilla/Товары/Торговые корабли|Торговые корабли]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_clerks_add` = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_bureaucrats_add` = `100` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `10`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_port)|Основа (pmg_base_building_port)]]
