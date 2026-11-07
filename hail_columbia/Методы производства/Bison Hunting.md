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
    - [[vanilla/движок/Модификаторы G#^m-goods-input-small-arms-add|goods_input_small_arms_add]] = `1` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-ammunition-add|goods_input_ammunition_add]] = `1` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silk-add|goods_output_silk_add]] = `8` → [[vanilla/Товары/Шёлк|Шёлк]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `3` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы B#^m-building-group-bg-ranching-construction-efficiency-add|building_group_bg_ranching_construction_efficiency_add]] = `0.02`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `300` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-soldiers-add|building_employment_soldiers_add]] = `200` → [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]]
    - [[vanilla/движок/Модификаторы S#^m-state-animist-standard-of-living-add|state_animist_standard_of_living_add]] = `-0.5`

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Pelt Hunting|Pelt Hunting]]
