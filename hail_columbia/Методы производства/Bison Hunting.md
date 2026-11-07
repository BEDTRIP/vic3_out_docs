---
type: concept
description: "Метод производства «Bison Hunting» — Hail Columbia 1.13, `usfp_pm_bison_hunting`"
project: vic3
source: hail_columbia
aliases: ["Bison Hunting", "usfp_pm_bison_hunting"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usfp_pm_bison_hunting
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Bison Hunting

Метод производства · `usfp_pm_bison_hunting` · `common/production_methods/usfp_production_methods.txt:44`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_bison_hunting.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Магазины|Магазины]]
- **unlocking_geographic_regions**: `geographic_region_american_bison_range`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_small_arms_add` = `1` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
    - `goods_input_ammunition_add` = `1` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
    - `goods_output_silk_add` = `8` → [[vanilla/Товары/Шёлк|Шёлк]]
    - `goods_output_fabric_add` = `3` → [[vanilla/Товары/Ткань|Ткань]]
    - `building_group_bg_ranching_construction_efficiency_add` = `0.02`
  - **level_scaled**:
    - `building_employment_laborers_add` = `300` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_soldiers_add` = `200` → [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]]
    - `state_animist_standard_of_living_add` = `-0.5`

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Pelt Hunting|Pelt Hunting]]
