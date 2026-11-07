---
type: concept
description: "Метод производства «Basic Oversight (pm_wood_point_conversion)» — PSC 1.13, `pm_wood_point_conversion`"
project: vic3
source: psc
aliases: ["Basic Oversight (pm_wood_point_conversion)", "Basic Oversight", "pm_wood_point_conversion"]
tags: [PSC, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_wood_point_conversion
paths: [PSC/common/production_methods/zz_PSC_construction.txt]
---
# Basic Oversight (pm_wood_point_conversion)

Метод производства · `pm_wood_point_conversion` · `common/production_methods/zz_PSC_construction.txt:128`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/construction_bureaucrats.dds`
- **is_default**: `yes`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-construction-add|country_construction_add]] = `1`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-construction-add|goods_input_wood_construction_add]] = `10` → [[psc/Товары/Wood Construction|Wood Construction]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `20` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
- **unlocking_production_methods**: `pm_wood_point_conversion`

## Ссылаются

- **Группы методов** (методы группы): [[psc/Группы методов/Основа|Основа]]
