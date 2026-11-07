---
type: concept
description: "Метод производства «Subsistence Hunting» — Hail Columbia 1.13, `usfp_pm_subsistence_hunting`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Subsistence Hunting", "usfp_pm_subsistence_hunting"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usfp_pm_subsistence_hunting
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Subsistence Hunting

Метод производства · `usfp_pm_subsistence_hunting` · `common/production_methods/usfp_production_methods.txt:72`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_bow_and_arrow.dds`
- **unlocking_laws**: [[hail_columbia/Законы/Land Stewardship|Land Stewardship]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silk-add|goods_output_silk_add]] = `1` → [[vanilla/Товары/Шёлк|Шёлк]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `1` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `1` → [[vanilla/Товары/Мясо|Мясо]]
    - [[vanilla/движок/Модификаторы B#^m-building-subsistence-output-add|building_subsistence_output_add]] = `4`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-soldiers-add|building_employment_soldiers_add]] = `100` → [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]]

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Pelt Hunting|Pelt Hunting]]
