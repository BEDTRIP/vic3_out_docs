---
type: concept
description: "Метод производства «Civil Plane» — T&R 1.13, `pm_civil_planes_production`"
project: vic3
source: tr
aliases: ["Civil Plane", "pm_civil_planes_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_civil_planes_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Civil Plane

Метод производства · `pm_civil_planes_production` · `common/production_methods/ztr_military_production_methods.txt:233`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/civil_planes_production.dds`
- **unlocking_technologies**: [[tr/Технологии/Jet Engines|Jet Engines]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `25` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_glass_add` = `5` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_aluminium_add` = `20` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_electroniccomponents_add` = `15` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_civil_planes_add` = `80` → [[tr/Товары/Airplanes|Airplanes]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aeronautics & Astronautics Production|Aeronautics & Astronautics Production]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Modern Warplanes Production|Modern Warplanes Production]], [[tr/Методы производства/Supersonic Jet Warplanes|Supersonic Jet Warplanes]]
