---
type: concept
description: "Метод производства «Spacecraft» — T&R 1.13, `pm_rocket_spacecraft`"
project: vic3
source: tr
aliases: ["Spacecraft", "pm_rocket_spacecraft"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rocket_spacecraft
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Spacecraft

Метод производства · `pm_rocket_spacecraft` · `common/production_methods/ztr_new_production_methods.txt:7933`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/space_rocket.dds`
- **unlocking_technologies**: [[tr/Технологии/Astronautics|Astronautics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `15` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_alloys_add` = `35` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_computer_add` = `10` → [[tr/Товары/Computers|Computers]]
    - `goods_input_engines_add` = `20` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_robotics_add` = `15` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_light_fuel_add` = `50` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_space_assets_add` = `70` → [[tr/Товары/Space Assets|Space Assets]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_academics_add` = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aeronautics & Astronautics Production|Aeronautics & Astronautics Production]]
