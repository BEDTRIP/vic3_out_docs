---
type: concept
description: "Метод производства «Picks and Shovels (pm_curie_picks_and_shovels_building_uranium_mine)» — T&R 1.13, `pm_curie_picks_and_shovels_building_uranium_mine`"
project: vic3
source: tr
aliases: ["Picks and Shovels (pm_curie_picks_and_shovels_building_uranium_mine)", "Picks and Shovels", "pm_curie_picks_and_shovels_building_uranium_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_curie_picks_and_shovels_building_uranium_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Picks and Shovels (pm_curie_picks_and_shovels_building_uranium_mine)

Метод производства · `pm_curie_picks_and_shovels_building_uranium_mine` · `common/production_methods/ztr_modified_mr_production_methods.txt:895`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_good_uranium_add` = `20` → [[tr/Товары/Uranium|Uranium]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.3`
    - `building_machinists_mortality_mult` = `0.2`
    - `building_engineers_mortality_mult` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)|Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)]]
