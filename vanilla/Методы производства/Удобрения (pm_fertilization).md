---
type: concept
description: "Метод производства «Удобрения (pm_fertilization)» — ваниль 1.13, `pm_fertilization`"
project: vic3
audience: agent
source: vanilla
aliases: ["Удобрения (pm_fertilization)", "Fertilizers", "pm_fertilization"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fertilization
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Удобрения (pm_fertilization)

Метод производства · `pm_fertilization` · `common/production_methods/02_agro.txt:66`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/fertilization.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Улучшенное удобрение|Улучшенное удобрение]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-drought-impact-mult|state_harvest_condition_drought_impact_mult]] = `0.05`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `45` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `2000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_maize_farm)|Основа (pmg_base_building_maize_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_millet_farm)|Основа (pmg_base_building_millet_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_rye_farm)|Основа (pmg_base_building_rye_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_wheat_farm)|Основа (pmg_base_building_wheat_farm)]]
