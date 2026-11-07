---
type: concept
description: "Метод производства «Кирки и лопаты (pm_picks_and_shovels_building_gold_mine)» — ваниль 1.13, `pm_picks_and_shovels_building_gold_mine`"
project: vic3
source: vanilla
aliases: ["Кирки и лопаты (pm_picks_and_shovels_building_gold_mine)", "Picks and Shovels", "pm_picks_and_shovels_building_gold_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_picks_and_shovels_building_gold_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Кирки и лопаты (pm_picks_and_shovels_building_gold_mine)

Метод производства · `pm_picks_and_shovels_building_gold_mine` · `common/production_methods/03_mines.txt:787`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-gold-add|goods_output_gold_add]] = `8` → [[vanilla/Товары/Золото|Золото]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-minting-add|country_minting_add]] = `250`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_gold_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_gold_mine)]]
