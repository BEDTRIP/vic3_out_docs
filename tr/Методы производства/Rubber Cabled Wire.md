---
type: concept
description: "Метод производства «Rubber Cabled Wire» — T&R 1.13, `pm_cabled_copperwires`"
project: vic3
source: tr
aliases: ["Rubber Cabled Wire", "pm_cabled_copperwires"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cabled_copperwires
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Rubber Cabled Wire

Метод производства · `pm_cabled_copperwires` · `common/production_methods/ztr_new_production_methods.txt:4076`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/cabled_copperwires.dds`
- **unlocking_technologies**: [[tr/Технологии/Cabled Wire|Cabled Wire]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `40` → [[tr/Товары/Copper|Copper]]
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_rubber_add` = `10` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_output_copperwires_add` = `75` → [[tr/Товары/Wires|Wires]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **ai_value**: `1000`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Wire|Wire]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Embedded Control Circuit|Embedded Control Circuit]]
