---
type: concept
description: "Метод производства «Turbo-Diesel Engines» — T&R 1.13, `pm_turbo_diesel_engines`"
project: vic3
source: tr
aliases: ["Turbo-Diesel Engines", "pm_turbo_diesel_engines"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_turbo_diesel_engines
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Turbo-Diesel Engines

Метод производства · `pm_turbo_diesel_engines` · `common/production_methods/ztr_new_production_methods.txt:2138`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_turbo_diesel_engines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Thermal Cracking|Thermal Cracking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `40` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_light_fuel_add` = `10` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - `goods_output_engines_add` = `140` → [[vanilla/Товары/Двигатели|Двигатели]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_motor_industry)|Основа (pmg_base_building_motor_industry)]]
