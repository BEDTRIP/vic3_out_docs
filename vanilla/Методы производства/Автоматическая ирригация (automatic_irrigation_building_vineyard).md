---
type: concept
description: "Метод производства «Автоматическая ирригация (automatic_irrigation_building_vineyard)» — ваниль 1.13, `automatic_irrigation_building_vineyard`"
project: vic3
audience: agent
source: vanilla
aliases: ["Автоматическая ирригация (automatic_irrigation_building_vineyard)", "Автоматическая ирригация", "automatic_irrigation_building_vineyard"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: automatic_irrigation_building_vineyard
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Автоматическая ирригация (automatic_irrigation_building_vineyard)

Метод производства · `automatic_irrigation_building_vineyard` · `common/production_methods/02_agro.txt:689`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/automatic_irrigation.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Качалки|Качалки]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wine-add|goods_output_wine_add]] = `40` → [[vanilla/Товары/Вино|Вино]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_vineyard)|Основа (pmg_base_building_vineyard)]]
