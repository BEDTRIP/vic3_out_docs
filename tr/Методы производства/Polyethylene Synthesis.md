---
type: concept
description: "Метод производства «Polyethylene Synthesis» — T&R 1.13, `pm_polyethylene_synthesis`"
project: vic3
source: tr
aliases: ["Polyethylene Synthesis", "pm_polyethylene_synthesis"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_polyethylene_synthesis
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Polyethylene Synthesis

Метод производства · `pm_polyethylene_synthesis` · `common/production_methods/ztr_new_production_methods.txt:3751`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_polyethylene_synthesis.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **unlocking_technologies**: [[tr/Технологии/Ethylene|Ethylene]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_light_fuel_add` = `25` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_plastics_add` = `100` → [[tr/Товары/Пластмассы|Пластмассы]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
- **ai_value**: `2000`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Plastics & Rubber production|Plastics & Rubber production]]
