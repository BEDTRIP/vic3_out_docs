---
type: concept
description: "Метод производства «Базовое производство (default_building_tea_plantation)» — ваниль 1.13, `default_building_tea_plantation`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_tea_plantation)", "Базовое производство", "default_building_tea_plantation"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_tea_plantation
paths: [.vanillaVIC3/common/production_methods/04_plantations.txt]
---
# Базовое производство (default_building_tea_plantation)

Метод производства · `default_building_tea_plantation` · `common/production_methods/04_plantations.txt:300`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/plantation_production.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_tea_add` = `20` → [[vanilla/Товары/Чай|Чай]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `6000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_tea_plantation)|Основа (pmg_base_building_tea_plantation)]]
