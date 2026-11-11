---
type: concept
description: "Метод производства «Земледелие с использованием удобрений (pm_soil_enriching_farming_building_rice_farm)» — ваниль 1.15, `pm_soil_enriching_farming_building_rice_farm`"
project: vic3
audience: agent
source: vanilla
aliases: ["Земледелие с использованием удобрений (pm_soil_enriching_farming_building_rice_farm)", "Soil-Enriching Farming", "pm_soil_enriching_farming_building_rice_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_soil_enriching_farming_building_rice_farm
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Земледелие с использованием удобрений (pm_soil_enriching_farming_building_rice_farm)

Метод производства · `pm_soil_enriching_farming_building_rice_farm` · `common/production_methods/02_agro.txt:320`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/soil_enriching_farming.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Интенсивное сельское хозяйство|Интенсивное сельское хозяйство]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `50` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `7000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `3000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-slaves-mortality-mult|building_slaves_mortality_mult]] = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
