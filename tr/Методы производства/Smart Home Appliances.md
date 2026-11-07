---
type: concept
description: "Метод производства «Smart Home Appliances» — T&R 1.13, `pm_smart_homeappliances`"
project: vic3
source: tr
aliases: ["Smart Home Appliances", "pm_smart_homeappliances"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smart_homeappliances
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Smart Home Appliances

Метод производства · `pm_smart_homeappliances` · `common/production_methods/ztr_new_production_methods.txt:6170`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_smart_homeappliances.dds`
- **unlocking_technologies**: [[tr/Технологии/Smart Appliances|Smart Appliances]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `25` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_steel_add` = `50` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electricity_add` = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `20` → [[tr/Товары/Processors|Processors]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_telecommunications_add` = `30` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_homeappliances_add` = `110` → [[tr/Товары/Home Appliances|Home Appliances]]
  - **level_scaled**:
    - `building_employment_academics_add` = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_machinists_add` = `2250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Home Appliance|Home Appliance]]
