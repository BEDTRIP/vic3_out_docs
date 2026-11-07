---
type: concept
description: "Метод производства «Земледелие с использованием удобрений (pm_soil_enriching_farming)» — ваниль 1.13, `pm_soil_enriching_farming`"
project: vic3
source: vanilla
aliases: ["Земледелие с использованием удобрений (pm_soil_enriching_farming)", "Soil-Enriching Farming", "pm_soil_enriching_farming"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_soil_enriching_farming
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Земледелие с использованием удобрений (pm_soil_enriching_farming)

Метод производства · `pm_soil_enriching_farming` · `common/production_methods/02_agro.txt:42`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/soil_enriching_farming.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Интенсивное сельское хозяйство|Интенсивное сельское хозяйство]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_output_grain_add` = `30` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `3500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_maize_farm)|Основа (pmg_base_building_maize_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_millet_farm)|Основа (pmg_base_building_millet_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_rye_farm)|Основа (pmg_base_building_rye_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_wheat_farm)|Основа (pmg_base_building_wheat_farm)]]
