---
type: concept
description: "Метод производства «Удобрения (pm_fertilization_building_rice_farm)» — ваниль 1.13, `pm_fertilization_building_rice_farm`"
project: vic3
source: vanilla
aliases: ["Удобрения (pm_fertilization_building_rice_farm)", "Fertilizers", "pm_fertilization_building_rice_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fertilization_building_rice_farm
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Удобрения (pm_fertilization_building_rice_farm)

Метод производства · `pm_fertilization_building_rice_farm` · `common/production_methods/02_agro.txt:347`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/fertilization.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Улучшенное удобрение|Улучшенное удобрение]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `20` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_output_grain_add` = `75` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `6000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `4000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
