---
type: concept
description: "Метод производства «Простое земледелие (pm_simple_farming_building_rice_farm)» — ваниль 1.13, `pm_simple_farming_building_rice_farm`"
project: vic3
source: vanilla
aliases: ["Простое земледелие (pm_simple_farming_building_rice_farm)", "Simple Farming", "pm_simple_farming_building_rice_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_simple_farming_building_rice_farm
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Простое земледелие (pm_simple_farming_building_rice_farm)

Метод производства · `pm_simple_farming_building_rice_farm` · `common/production_methods/02_agro.txt:273`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/simple_farming.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `35` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `8000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `2000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
  - **unscaled**:
    - `building_slaves_mortality_mult` = `0.2`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
