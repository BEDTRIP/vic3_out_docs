---
type: concept
description: "Метод производства «Picks and Shovels» — E&F 1.13, `pm_picks_and_shovels_building_silver_mine`"
project: vic3
source: ef
aliases: ["Picks and Shovels", "pm_picks_and_shovels_building_silver_mine"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_picks_and_shovels_building_silver_mine
paths: [E&F/common/production_methods/03_ef_mines.txt]
---
# Picks and Shovels

Метод производства · `pm_picks_and_shovels_building_silver_mine` · `common/production_methods/03_ef_mines.txt:62`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silver-add|goods_output_silver_add]] = `25` → [[ef/Товары/Silver|Silver]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Mining Equipment|Mining Equipment]]
