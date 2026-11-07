---
type: concept
description: "Метод производства «Удобрения из рыбных отходов (pm_herring_meal_farming_building_rice_farm)» — ваниль 1.13, `pm_herring_meal_farming_building_rice_farm`"
project: vic3
source: vanilla
aliases: ["Удобрения из рыбных отходов (pm_herring_meal_farming_building_rice_farm)", "Удобрения из рыбных отходов", "pm_herring_meal_farming_building_rice_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_herring_meal_farming_building_rice_farm
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Удобрения из рыбных отходов (pm_herring_meal_farming_building_rice_farm)

Метод производства · `pm_herring_meal_farming_building_rice_farm` · `common/production_methods/02_agro.txt:291`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/simple_fishing.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_geographic_regions**: `geographic_region_japan`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fish-add|goods_input_fish_add]] = `10` → [[vanilla/Товары/Рыба|Рыба]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `45` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `8000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `2000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-slaves-mortality-mult|building_slaves_mortality_mult]] = `0.2`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
