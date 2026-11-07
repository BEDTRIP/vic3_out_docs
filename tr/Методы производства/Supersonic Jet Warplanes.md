---
type: concept
description: "Метод производства «Supersonic Jet Warplanes» — T&R 1.13, `pm_supersonic_warplanes_production`"
project: vic3
source: tr
aliases: ["Supersonic Jet Warplanes", "pm_supersonic_warplanes_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_supersonic_warplanes_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Supersonic Jet Warplanes

Метод производства · `pm_supersonic_warplanes_production` · `common/production_methods/ztr_military_production_methods.txt:324`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_supersonic_warplanes_production_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Supersonic Aviation|Supersonic Aviation]]
- **unlocking_production_methods**: [[tr/Методы производства/Civil Plane|Civil Plane]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_computer_add` = `5` → [[tr/Товары/Computers|Computers]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_artillery_add` = `10` → [[vanilla/Товары/Артиллерия|Артиллерия]]
    - `goods_input_small_arms_add` = `20` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
    - `goods_output_civil_planes_add` = `-40` → [[tr/Товары/Airplanes|Airplanes]]
    - `goods_output_aeroplanes_add` = `75` → [[tr/Товары/Аэропланы|Аэропланы]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Аэропланы|Аэропланы]]
