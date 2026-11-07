---
type: concept
description: "Метод производства «Hand Pumped Water» — T&R 1.13, `pm_hand_pumped_water`"
project: vic3
source: tr
aliases: ["Hand Pumped Water", "pm_hand_pumped_water"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hand_pumped_water
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Hand Pumped Water

Метод производства · `pm_hand_pumped_water` · `common/production_methods/ztr_new_production_methods.txt:6376`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_hand_pumped_water.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `25` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_water_add` = `40` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Water|Water]]
