---
type: concept
description: "Метод производства «Advanced Plantation Harvesting (advanced_plantation_methods_building_dye_plantation)» — T&R 1.13, `advanced_plantation_methods_building_dye_plantation`"
project: vic3
source: tr
aliases: ["Advanced Plantation Harvesting (advanced_plantation_methods_building_dye_plantation)", "Advanced Plantation Harvesting", "advanced_plantation_methods_building_dye_plantation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: advanced_plantation_methods_building_dye_plantation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Advanced Plantation Harvesting (advanced_plantation_methods_building_dye_plantation)

Метод производства · `advanced_plantation_methods_building_dye_plantation` · `common/production_methods/ztr_agriculture_production_methods.txt:616`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mechanical_harvesting.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Heavy Machinery|Heavy Machinery]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_fertilizer_add` = `3` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_light_fuel_add` = `1` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_steel_add` = `2` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_output_dye_add` = `90` → [[vanilla/Товары/Красители|Красители]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_dye_plantation)|Основа (pmg_base_building_dye_plantation)]]
