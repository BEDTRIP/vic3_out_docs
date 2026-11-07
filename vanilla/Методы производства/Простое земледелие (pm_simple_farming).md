---
type: concept
description: "Метод производства «Простое земледелие (pm_simple_farming)» — ваниль 1.13, `pm_simple_farming`"
project: vic3
source: vanilla
aliases: ["Простое земледелие (pm_simple_farming)", "Simple Farming", "pm_simple_farming"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_simple_farming
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Простое земледелие (pm_simple_farming)

Метод производства · `pm_simple_farming` · `common/production_methods/02_agro.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/simple_farming.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `20` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_maize_farm)|Основа (pmg_base_building_maize_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_millet_farm)|Основа (pmg_base_building_millet_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_rye_farm)|Основа (pmg_base_building_rye_farm)]], [[vanilla/Группы методов/Основа (pmg_base_building_wheat_farm)|Основа (pmg_base_building_wheat_farm)]]
