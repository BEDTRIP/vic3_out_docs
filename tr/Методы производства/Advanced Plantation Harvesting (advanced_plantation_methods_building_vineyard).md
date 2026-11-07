---
type: concept
description: "Метод производства «Advanced Plantation Harvesting (advanced_plantation_methods_building_vineyard)» — T&R 1.13, `advanced_plantation_methods_building_vineyard`"
project: vic3
audience: agent
source: tr
aliases: ["Advanced Plantation Harvesting (advanced_plantation_methods_building_vineyard)", "Advanced Plantation Harvesting", "advanced_plantation_methods_building_vineyard"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: advanced_plantation_methods_building_vineyard
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Advanced Plantation Harvesting (advanced_plantation_methods_building_vineyard)

Метод производства · `advanced_plantation_methods_building_vineyard` · `common/production_methods/ztr_agriculture_production_methods.txt:272`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mechanical_harvesting.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Heavy Machinery|Heavy Machinery]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `20` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_light_fuel_add` = `2` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wine-add|goods_output_wine_add]] = `75` → [[vanilla/Товары/Вино|Вино]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_vineyard)|Основа (pmg_base_building_vineyard)]]
