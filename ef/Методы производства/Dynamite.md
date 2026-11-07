---
type: concept
description: "Метод производства «Dynamite» — E&F 1.13, `pm_dynamite_building_silver_mine`"
project: vic3
source: ef
aliases: ["Dynamite", "pm_dynamite_building_silver_mine"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dynamite_building_silver_mine
paths: [E&F/common/production_methods/03_ef_mines.txt]
---
# Dynamite

Метод производства · `pm_dynamite_building_silver_mine` · `common/production_methods/03_ef_mines.txt:213`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dynamite.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Динамит|Динамит]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `10` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silver-add|goods_output_silver_add]] = `25` → [[ef/Товары/Silver|Silver]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Explosives|Explosives]]
