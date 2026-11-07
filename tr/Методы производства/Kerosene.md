---
type: concept
description: "Метод производства «Kerosene» — T&R 1.13, `pm_airport_kerosene`"
project: vic3
source: tr
aliases: ["Kerosene", "pm_airport_kerosene"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_airport_kerosene
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Kerosene

Метод производства · `pm_airport_kerosene` · `common/production_methods/ztr_military_production_methods.txt:13`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_airport_kerosene.dds`
- **unlocking_technologies**: [[tr/Технологии/Aviation Fuel|Aviation Fuel]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Fuel|Fuel]]
