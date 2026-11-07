---
type: concept
description: "Метод производства «Rudimental Home Appliances» — T&R 1.13, `pm_rudimental_homeappliances`"
project: vic3
source: tr
aliases: ["Rudimental Home Appliances", "pm_rudimental_homeappliances"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rudimental_homeappliances
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Rudimental Home Appliances

Метод производства · `pm_rudimental_homeappliances` · `common/production_methods/ztr_new_production_methods.txt:6102`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_rudimental_homeappliances.dds`
- **unlocking_technologies**: [[tr/Технологии/Rudimental Appliances|Rudimental Appliances]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_copperwires_add` = `15` → [[tr/Товары/Wires|Wires]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_steel_add` = `25` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_homeappliances_add` = `40` → [[tr/Товары/Home Appliances|Home Appliances]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_machinists_add` = `2500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Home Appliance|Home Appliance]]
