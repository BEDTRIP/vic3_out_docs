---
type: concept
description: "Метод производства «Базовое производство (default_building_vineyard)» — ваниль 1.13, `default_building_vineyard`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_vineyard)", "Базовое производство", "default_building_vineyard"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_vineyard
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Базовое производство (default_building_vineyard)

Метод производства · `default_building_vineyard` · `common/production_methods/02_agro.txt:672`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/plantation_production.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_wine_add` = `20` → [[vanilla/Товары/Вино|Вино]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_vineyard)|Основа (pmg_base_building_vineyard)]]
