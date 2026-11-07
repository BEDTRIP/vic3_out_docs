---
type: concept
description: "Метод производства «Modern Warplanes Production» — T&R 1.13, `pm_modern_warplanes_production`"
project: vic3
audience: agent
source: tr
aliases: ["Modern Warplanes Production", "pm_modern_warplanes_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modern_warplanes_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Modern Warplanes Production

Метод производства · `pm_modern_warplanes_production` · `common/production_methods/ztr_military_production_methods.txt:294`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modern_warplanes_production_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Warplanes|Modern Warplanes]]
- **unlocking_production_methods**: [[tr/Методы производства/Zeppelin|Zeppelin]], [[tr/Методы производства/Civil Plane|Civil Plane]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-artillery-add|goods_input_artillery_add]] = `5` → [[vanilla/Товары/Артиллерия|Артиллерия]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-small-arms-add|goods_input_small_arms_add]] = `15` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
    - `goods_output_civil_planes_add` = `-35` → [[tr/Товары/Airplanes|Airplanes]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-aeroplanes-add|goods_output_aeroplanes_add]] = `55` → [[tr/Товары/Аэропланы|Аэропланы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Аэропланы|Аэропланы]]
