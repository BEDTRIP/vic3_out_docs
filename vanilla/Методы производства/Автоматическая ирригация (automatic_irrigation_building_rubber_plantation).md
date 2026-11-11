---
type: concept
description: "Метод производства «Автоматическая ирригация (automatic_irrigation_building_rubber_plantation)» — ваниль 1.15, `automatic_irrigation_building_rubber_plantation`"
project: vic3
audience: agent
source: vanilla
aliases: ["Автоматическая ирригация (automatic_irrigation_building_rubber_plantation)", "Автоматическая ирригация", "automatic_irrigation_building_rubber_plantation"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: automatic_irrigation_building_rubber_plantation
paths: [.vanillaVIC3/common/production_methods/09_misc_resource.txt]
---
# Автоматическая ирригация (automatic_irrigation_building_rubber_plantation)

Метод производства · `automatic_irrigation_building_rubber_plantation` · `common/production_methods/09_misc_resource.txt:214`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/automatic_irrigation.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Качалки|Качалки]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-rubber-add|goods_output_rubber_add]] = `40` → [[vanilla/Товары/Каучук|Каучук]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_rubber_plantation)|Основа (pmg_base_building_rubber_plantation)]]
