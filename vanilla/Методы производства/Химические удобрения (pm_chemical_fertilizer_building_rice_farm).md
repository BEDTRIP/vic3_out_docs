---
type: concept
description: "Метод производства «Химические удобрения (pm_chemical_fertilizer_building_rice_farm)» — ваниль 1.13, `pm_chemical_fertilizer_building_rice_farm`"
project: vic3
source: vanilla
aliases: ["Химические удобрения (pm_chemical_fertilizer_building_rice_farm)", "Chemical Fertilizers", "pm_chemical_fertilizer_building_rice_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_chemical_fertilizer_building_rice_farm
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Химические удобрения (pm_chemical_fertilizer_building_rice_farm)

Метод производства · `pm_chemical_fertilizer_building_rice_farm` · `common/production_methods/02_agro.txt:371`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/chemical_fertilizers.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Связывание азота|Связывание азота]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `30` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `100` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `5000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `5000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
