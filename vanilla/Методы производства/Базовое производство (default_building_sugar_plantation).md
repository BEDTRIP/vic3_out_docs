---
type: concept
description: "Метод производства «Базовое производство (default_building_sugar_plantation)» — ваниль 1.13, `default_building_sugar_plantation`"
project: vic3
audience: agent
source: vanilla
aliases: ["Базовое производство (default_building_sugar_plantation)", "Базовое производство", "default_building_sugar_plantation"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_sugar_plantation
paths: [.vanillaVIC3/common/production_methods/04_plantations.txt]
---
# Базовое производство (default_building_sugar_plantation)

Метод производства · `default_building_sugar_plantation` · `common/production_methods/04_plantations.txt:445`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/plantation_production.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sugar-add|goods_output_sugar_add]] = `25` → [[vanilla/Товары/Сахар|Сахар]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `9000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-laborers-mortality-mult|building_laborers_mortality_mult]] = `0.05`
    - [[vanilla/движок/Модификаторы B#^m-building-slaves-mortality-mult|building_slaves_mortality_mult]] = `0.1`
    - [[vanilla/движок/Модификаторы B#^m-building-slaves-standard-of-living-add|building_slaves_standard_of_living_add]] = `-1`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_sugar_plantation)|Основа (pmg_base_building_sugar_plantation)]]
