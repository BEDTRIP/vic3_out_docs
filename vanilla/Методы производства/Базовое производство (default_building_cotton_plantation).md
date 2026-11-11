---
type: concept
description: "Метод производства «Базовое производство (default_building_cotton_plantation)» — ваниль 1.15, `default_building_cotton_plantation`"
project: vic3
audience: agent
source: vanilla
aliases: ["Базовое производство (default_building_cotton_plantation)", "Базовое производство", "default_building_cotton_plantation"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_cotton_plantation
paths: [.vanillaVIC3/common/production_methods/04_plantations.txt]
---
# Базовое производство (default_building_cotton_plantation)

Метод производства · `default_building_cotton_plantation` · `common/production_methods/04_plantations.txt:162`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/plantation_production.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `45` → [[vanilla/Товары/Ткань|Ткань]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `7000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_cotton_plantation)|Основа (pmg_base_building_cotton_plantation)]]
