---
type: concept
description: "Метод производства «Basic Oversight (pm_arc_welded_point_conversion)» — PSC 1.13, `pm_arc_welded_point_conversion`"
project: vic3
source: psc
aliases: ["Basic Oversight (pm_arc_welded_point_conversion)", "Basic Oversight", "pm_arc_welded_point_conversion"]
tags: [PSC, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_arc_welded_point_conversion
paths: [PSC/common/production_methods/zz_PSC_construction.txt]
---
# Basic Oversight (pm_arc_welded_point_conversion)

Метод производства · `pm_arc_welded_point_conversion` · `common/production_methods/zz_PSC_construction.txt:200`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/construction_bureaucrats.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_construction_add` = `1`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_arc_welded_construction_add` = `10` → [[psc/Товары/Arc-Welded Construction|Arc-Welded Construction]]
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `20` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
- **unlocking_production_methods**: `pm_arc_welded_point_conversion`

## Ссылаются

- **Группы методов** (методы группы): [[psc/Группы методов/Основа|Основа]]
