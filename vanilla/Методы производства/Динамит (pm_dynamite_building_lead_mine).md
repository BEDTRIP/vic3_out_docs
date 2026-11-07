---
type: concept
description: "Метод производства «Динамит (pm_dynamite_building_lead_mine)» — ваниль 1.13, `pm_dynamite_building_lead_mine`"
project: vic3
source: vanilla
aliases: ["Динамит (pm_dynamite_building_lead_mine)", "Dynamite", "pm_dynamite_building_lead_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dynamite_building_lead_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Динамит (pm_dynamite_building_lead_mine)

Метод производства · `pm_dynamite_building_lead_mine` · `common/production_methods/03_mines.txt:589`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dynamite.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Динамит|Динамит]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_explosives_add` = `10` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_lead_add` = `20` → [[vanilla/Товары/Свинец|Свинец]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Взрывчатка (pmg_explosives_building_lead_mine)|Взрывчатка (pmg_explosives_building_lead_mine)]]
