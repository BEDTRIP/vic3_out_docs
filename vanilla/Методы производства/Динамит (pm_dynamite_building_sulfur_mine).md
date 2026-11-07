---
type: concept
description: "Метод производства «Динамит (pm_dynamite_building_sulfur_mine)» — ваниль 1.13, `pm_dynamite_building_sulfur_mine`"
project: vic3
source: vanilla
aliases: ["Динамит (pm_dynamite_building_sulfur_mine)", "Dynamite", "pm_dynamite_building_sulfur_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dynamite_building_sulfur_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Динамит (pm_dynamite_building_sulfur_mine)

Метод производства · `pm_dynamite_building_sulfur_mine` · `common/production_methods/03_mines.txt:760`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dynamite.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Динамит|Динамит]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_explosives_add` = `10` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_sulfur_add` = `20` → [[vanilla/Товары/Сера|Сера]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Взрывчатка (pmg_explosives_building_sulfur_mine)|Взрывчатка (pmg_explosives_building_sulfur_mine)]]
