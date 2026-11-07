---
type: concept
description: "Метод производства «Basic Home Appliances» — T&R 1.13, `pm_basic_homeappliances`"
project: vic3
source: tr
aliases: ["Basic Home Appliances", "pm_basic_homeappliances"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_homeappliances
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Basic Home Appliances

Метод производства · `pm_basic_homeappliances` · `common/production_methods/ztr_new_production_methods.txt:6136`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_basic_homeappliances.dds`
- **unlocking_technologies**: [[tr/Технологии/Basic Appliances|Basic Appliances]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `20` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_steel_add` = `40` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electricity_add` = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `25` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_homeappliances_add` = `75` → [[tr/Товары/Home Appliances|Home Appliances]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_machinists_add` = `2500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Home Appliance|Home Appliance]]
