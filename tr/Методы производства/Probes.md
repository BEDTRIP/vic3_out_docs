---
type: concept
description: "Метод производства «Probes» — T&R 1.13, `pm_rocket_probes`"
project: vic3
source: tr
aliases: ["Probes", "pm_rocket_probes"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rocket_probes
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Probes

Метод производства · `pm_rocket_probes` · `common/production_methods/ztr_new_production_methods.txt:7875`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/probes.dds`
- **unlocking_technologies**: [[tr/Технологии/Space Rocketry|Space Rocketry]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `15` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `20` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_space_assets_add` = `25` → [[tr/Товары/Space Assets|Space Assets]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_academics_add` = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aeronautics & Astronautics Production|Aeronautics & Astronautics Production]]
