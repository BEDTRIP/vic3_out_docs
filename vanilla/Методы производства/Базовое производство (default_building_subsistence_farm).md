---
type: concept
description: "Метод производства «Базовое производство (default_building_subsistence_farm)» — ваниль 1.13, `default_building_subsistence_farm`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_subsistence_farm)", "Базовое производство", "default_building_subsistence_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_subsistence_farm
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Базовое производство (default_building_subsistence_farm)

Метод производства · `default_building_subsistence_farm` · `common/production_methods/12_subsistence.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/subsistence_farming.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `1.0` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `0.5` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wood-add|goods_output_wood_add]] = `0.5` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `0.5` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-peasants-add|building_employment_peasants_add]] = `5000` → [[vanilla/Население/Типы/Крестьяне|Крестьяне]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_subsistence_farm)|Основа (pmg_base_building_subsistence_farm)]]
