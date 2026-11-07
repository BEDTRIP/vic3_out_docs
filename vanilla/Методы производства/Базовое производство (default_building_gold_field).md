---
type: concept
description: "Метод производства «Базовое производство (default_building_gold_field)» — ваниль 1.13, `default_building_gold_field`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_gold_field)", "Базовое производство", "default_building_gold_field"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_gold_field
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Базовое производство (default_building_gold_field)

Метод производства · `default_building_gold_field` · `common/production_methods/03_mines.txt:994`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gold_mining.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_gold_add` = `10` → [[vanilla/Товары/Золото|Золото]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_add` = `500`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_gold_field)|Основа (pmg_base_building_gold_field)]]
