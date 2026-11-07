---
type: concept
description: "Метод производства «Автоматическая ирригация (automatic_irrigation_building_tobacco_plantation)» — ваниль 1.13, `automatic_irrigation_building_tobacco_plantation`"
project: vic3
source: vanilla
aliases: ["Автоматическая ирригация (automatic_irrigation_building_tobacco_plantation)", "Автоматическая ирригация", "automatic_irrigation_building_tobacco_plantation"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: automatic_irrigation_building_tobacco_plantation
paths: [.vanillaVIC3/common/production_methods/04_plantations.txt]
---
# Автоматическая ирригация (automatic_irrigation_building_tobacco_plantation)

Метод производства · `automatic_irrigation_building_tobacco_plantation` · `common/production_methods/04_plantations.txt:363`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/automatic_irrigation.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Качалки|Качалки]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_tobacco_add` = `45` → [[vanilla/Товары/Табак|Табак]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_tobacco_plantation)|Основа (pmg_base_building_tobacco_plantation)]]
