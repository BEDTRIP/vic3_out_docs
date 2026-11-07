---
type: concept
description: "Метод производства «Нитроглицерин (pm_nitroglycerin_building_gold_mine)» — ваниль 1.13, `pm_nitroglycerin_building_gold_mine`"
project: vic3
source: vanilla
aliases: ["Нитроглицерин (pm_nitroglycerin_building_gold_mine)", "Nitroglycerin", "pm_nitroglycerin_building_gold_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nitroglycerin_building_gold_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Нитроглицерин (pm_nitroglycerin_building_gold_mine)

Метод производства · `pm_nitroglycerin_building_gold_mine` · `common/production_methods/03_mines.txt:923`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/nitroglycerin.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Нитроглицерин|Нитроглицерин]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_explosives_add` = `5` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_gold_add` = `5` → [[vanilla/Товары/Золото|Золото]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.3`
    - `building_machinists_mortality_mult` = `0.2`
    - `building_engineers_mortality_mult` = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_add` = `125`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Взрывчатка (pmg_explosives_building_gold_mine)|Взрывчатка (pmg_explosives_building_gold_mine)]]
