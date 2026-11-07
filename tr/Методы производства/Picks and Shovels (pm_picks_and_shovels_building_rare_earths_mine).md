---
type: concept
description: "Метод производства «Picks and Shovels (pm_picks_and_shovels_building_rare_earths_mine)» — T&R 1.13, `pm_picks_and_shovels_building_rare_earths_mine`"
project: vic3
source: tr
aliases: ["Picks and Shovels (pm_picks_and_shovels_building_rare_earths_mine)", "Picks and Shovels", "pm_picks_and_shovels_building_rare_earths_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_picks_and_shovels_building_rare_earths_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Picks and Shovels (pm_picks_and_shovels_building_rare_earths_mine)

Метод производства · `pm_picks_and_shovels_building_rare_earths_mine` · `common/production_methods/ztr_new_production_methods.txt:8515`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `50`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_rare_earths_add` = `20` → [[tr/Товары/Rare Earths|Rare Earths]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.2`
    - `building_machinists_mortality_mult` = `0.1`
    - `building_engineers_mortality_mult` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_rare_earths_mine)|Mining Equipment (pmg_mining_equipment_building_rare_earths_mine)]]
