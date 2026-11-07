---
type: concept
description: "Метод производства «Vertically Integrated Cultivation» — VC 1.13, `united_fruit_banana`"
project: vic3
source: vc
aliases: ["Vertically Integrated Cultivation", "united_fruit_banana"]
tags: [VC, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: united_fruit_banana
paths: [VC/common/production_methods/joi_methods.txt]
---
# Vertically Integrated Cultivation

Метод производства · `united_fruit_banana` · `common/production_methods/joi_methods.txt:145`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/radio_stations.dds`
- **state_modifiers**:
  - **unscaled**:
    - `state_migration_pull_mult` = `-0.1`
- **unlocking_technologies**: [[vc/Технологии/Vertically Integrated Plantations|Vertically Integrated Plantations]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_fruit_add` = `45` → [[vanilla/Товары/Фрукты|Фрукты]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.1`
    - `building_laborers_job_attractiveness_mult` = `-0.25`
    - `building_minimum_wage_mult` = `-0.15`

## Ссылаются

- **Группы методов** (методы группы): [[vc/Группы методов/Условия труда|Условия труда]]
