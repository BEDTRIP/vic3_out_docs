---
type: concept
description: "Метод производства «Picks and Shovels (pm_picks_and_shovels_building_bauxite_mine)» — T&R 1.13, `pm_picks_and_shovels_building_bauxite_mine`"
project: vic3
source: tr
aliases: ["Picks and Shovels (pm_picks_and_shovels_building_bauxite_mine)", "Picks and Shovels", "pm_picks_and_shovels_building_bauxite_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_picks_and_shovels_building_bauxite_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Picks and Shovels (pm_picks_and_shovels_building_bauxite_mine)

Метод производства · `pm_picks_and_shovels_building_bauxite_mine` · `common/production_methods/ztr_new_production_methods.txt:5393`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_bauxite_add` = `20` → [[tr/Товары/Bauxite|Bauxite]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_bauxite_mine)|Mining Equipment (pmg_mining_equipment_building_bauxite_mine)]]
