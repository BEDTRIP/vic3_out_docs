---
type: concept
description: "Метод производства «Satellites» — T&R 1.13, `pm_rocket_satellites`"
project: vic3
source: tr
aliases: ["Satellites", "pm_rocket_satellites"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rocket_satellites
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Satellites

Метод производства · `pm_rocket_satellites` · `common/production_methods/ztr_new_production_methods.txt:7903`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/satellites.dds`
- **unlocking_technologies**: [[tr/Технологии/Satellites|Satellites]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `15` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `10` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `15` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `25` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_space_assets_add` = `40` → [[tr/Товары/Space Assets|Space Assets]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aeronautics & Astronautics Production|Aeronautics & Astronautics Production]]
