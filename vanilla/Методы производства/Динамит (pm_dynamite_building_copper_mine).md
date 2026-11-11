---
type: concept
description: "Метод производства «Динамит (pm_dynamite_building_copper_mine)» — ваниль 1.15, `pm_dynamite_building_copper_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Динамит (pm_dynamite_building_copper_mine)", "Динамит", "pm_dynamite_building_copper_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dynamite_building_copper_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Динамит (pm_dynamite_building_copper_mine)

Метод производства · `pm_dynamite_building_copper_mine` · `common/production_methods/03_mines.txt:1163`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dynamite.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Динамит|Динамит]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `10` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_copper_add` = `20` → [[vanilla/Товары/Медь|Медь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Взрывчатка (pmg_explosives_building_copper_mine)|Взрывчатка (pmg_explosives_building_copper_mine)]]
