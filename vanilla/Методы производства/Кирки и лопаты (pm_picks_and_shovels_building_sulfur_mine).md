---
type: concept
description: "Метод производства «Кирки и лопаты (pm_picks_and_shovels_building_sulfur_mine)» — ваниль 1.15, `pm_picks_and_shovels_building_sulfur_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Кирки и лопаты (pm_picks_and_shovels_building_sulfur_mine)", "Picks and Shovels", "pm_picks_and_shovels_building_sulfur_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_picks_and_shovels_building_sulfur_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Кирки и лопаты (pm_picks_and_shovels_building_sulfur_mine)

Метод производства · `pm_picks_and_shovels_building_sulfur_mine` · `common/production_methods/03_mines.txt:615`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sulfur-add|goods_output_sulfur_add]] = `20` → [[vanilla/Товары/Сера|Сера]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_sulfur_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_sulfur_mine)]]
