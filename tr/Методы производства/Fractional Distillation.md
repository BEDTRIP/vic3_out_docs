---
type: concept
description: "Метод производства «Fractional Distillation» — T&R 1.13, `pm_fractional_distillation`"
project: vic3
source: tr
aliases: ["Fractional Distillation", "pm_fractional_distillation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fractional_distillation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Fractional Distillation

Метод производства · `pm_fractional_distillation` · `common/production_methods/ztr_new_production_methods.txt:3499`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/patent_stills.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[tr/Технологии/Oil Distillation|Oil Distillation]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_oil_add` = `65` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_light_fuel_add` = `30` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_lubricant_add` = `15` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_output_heavy_fuel_add` = `25` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/FuelOil production|FuelOil production]]
