---
type: concept
description: "Метод производства «Modular Fuel Ships» — T&R 1.13, `pm_modular_shipbuilding`"
project: vic3
source: tr
aliases: ["Modular Fuel Ships", "pm_modular_shipbuilding"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modular_shipbuilding
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modular Fuel Ships

Метод производства · `pm_modular_shipbuilding` · `common/production_methods/ztr_new_production_methods.txt:10253`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modular_shipbuilding.dds`
- **unlocking_technologies**: [[tr/Технологии/Modular Shipbuilding|Modular Shipbuilding]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_ship_construction_add` = `25`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `15` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electricity_add` = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_aluminium_add` = `15` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_processors_add` = `5` → [[tr/Товары/Processors|Processors]]
    - `goods_input_robotics_add` = `10` → [[tr/Товары/Robotics|Robotics]]
    - `goods_output_steamers_add` = `105` → [[vanilla/Товары/Пароходы|Пароходы]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_shipyard)|Основа (pmg_base_building_shipyard)]]
