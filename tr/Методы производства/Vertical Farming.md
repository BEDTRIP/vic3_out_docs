---
type: concept
description: "Метод производства «Vertical Farming» — T&R 1.13, `pm_hydroponic_vertical_farming`"
project: vic3
source: tr
aliases: ["Vertical Farming", "pm_hydroponic_vertical_farming"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hydroponic_vertical_farming
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Vertical Farming

Метод производства · `pm_hydroponic_vertical_farming` · `common/production_methods/ztr_new_production_methods.txt:6640`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_hydroponic_vertical_farming.dds`
- **unlocking_technologies**: [[tr/Технологии/Vertical Farming|Vertical Farming]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_fertilizer_add` = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_water_add` = `2` → [[tr/Товары/Water|Water]]
  - **unscaled**:
    - `building_throughput_add` = `0.75`
  - **level_scaled**:
    - `building_employment_farmers_add` = `2750` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - `building_employment_laborers_add` = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroponic Equipment|Hydroponic Equipment]]
