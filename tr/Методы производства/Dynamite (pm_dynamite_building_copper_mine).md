---
type: concept
description: "Метод производства «Dynamite (pm_dynamite_building_copper_mine)» — T&R 1.13, `pm_dynamite_building_copper_mine`"
project: vic3
source: tr
aliases: ["Dynamite (pm_dynamite_building_copper_mine)", "Dynamite", "pm_dynamite_building_copper_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dynamite_building_copper_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Dynamite (pm_dynamite_building_copper_mine)

Метод производства · `pm_dynamite_building_copper_mine` · `common/production_methods/ztr_new_production_methods.txt:5034`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dynamite.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Динамит|Динамит]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `10` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_copper_add` = `20` → [[tr/Товары/Copper|Copper]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Explosives (pmg_explosives_building_copper_mine)|Explosives (pmg_explosives_building_copper_mine)]]
