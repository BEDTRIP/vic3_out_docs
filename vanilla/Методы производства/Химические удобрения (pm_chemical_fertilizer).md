---
type: concept
description: "Метод производства «Химические удобрения (pm_chemical_fertilizer)» — ваниль 1.13, `pm_chemical_fertilizer`"
project: vic3
audience: agent
source: vanilla
aliases: ["Химические удобрения (pm_chemical_fertilizer)", "Chemical Fertilizers", "pm_chemical_fertilizer"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_chemical_fertilizer
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Химические удобрения (pm_chemical_fertilizer)

Метод производства · `pm_chemical_fertilizer` · `common/production_methods/02_agro.txt:96`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/chemical_fertilizers.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Связывание азота|Связывание азота]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-drought-impact-mult|state_harvest_condition_drought_impact_mult]] = `0.1`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `15` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `60` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `2500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_maize_farm)|Основа (pmg_base_building_maize_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_millet_farm)|Основа (pmg_base_building_millet_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_rye_farm)|Основа (pmg_base_building_rye_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_wheat_farm)|Основа (pmg_base_building_wheat_farm)]]
