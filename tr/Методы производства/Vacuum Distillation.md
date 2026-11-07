---
type: concept
description: "Метод производства «Vacuum Distillation» — T&R 1.13, `pm_vacuum_distillation`"
project: vic3
source: tr
aliases: ["Vacuum Distillation", "pm_vacuum_distillation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_vacuum_distillation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Vacuum Distillation

Метод производства · `pm_vacuum_distillation` · `common/production_methods/ztr_new_production_methods.txt:3532`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_vacuum_distillation.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[tr/Технологии/Vacuum Distillation|Vacuum Distillation]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_oil_add` = `90` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_lubricant_add` = `50` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_output_heavy_fuel_add` = `70` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/FuelOil production|FuelOil production]]
