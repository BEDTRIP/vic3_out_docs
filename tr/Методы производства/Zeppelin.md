---
type: concept
description: "Метод производства «Zeppelin» — T&R 1.13, `pm_zeppelins_production`"
project: vic3
source: tr
aliases: ["Zeppelin", "pm_zeppelins_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_zeppelins_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Zeppelin

Метод производства · `pm_zeppelins_production` · `common/production_methods/ztr_military_production_methods.txt:206`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/zeppelins.dds`
- **unlocking_technologies**: [[tr/Технологии/Дирижабли|Дирижабли]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_aluminium_add` = `5` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_fabric_add` = `80` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_civil_planes_add` = `50` → [[tr/Товары/Airplanes|Airplanes]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aeronautics & Astronautics Production|Aeronautics & Astronautics Production]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Modern Warplanes Production|Modern Warplanes Production]], [[tr/Методы производства/Производство аэропланов|Производство аэропланов]]
