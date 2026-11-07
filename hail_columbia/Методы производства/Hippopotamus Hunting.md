---
type: concept
description: "Метод производства «Hippopotamus Hunting» — Hail Columbia 1.13, `usfp_pm_hippo_hunting`"
project: vic3
source: hail_columbia
aliases: ["Hippopotamus Hunting", "usfp_pm_hippo_hunting"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usfp_pm_hippo_hunting
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Hippopotamus Hunting

Метод производства · `usfp_pm_hippo_hunting` · `common/production_methods/usfp_production_methods.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hippo_hunting.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_small_arms_add` = `10` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
    - `goods_output_meat_add` = `30` → [[vanilla/Товары/Мясо|Мясо]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.3`
- **state_modifiers**:
  - **level_scaled**:
    - `state_pollution_generation_add` = `10`

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Hippopotamus Hunting|Hippopotamus Hunting]]
