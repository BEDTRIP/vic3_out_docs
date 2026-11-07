---
type: concept
description: "Метод производства «Dynamite (pm_dynamite_building_bauxite_mine)» — T&R 1.13, `pm_dynamite_building_bauxite_mine`"
project: vic3
source: tr
aliases: ["Dynamite (pm_dynamite_building_bauxite_mine)", "Dynamite", "pm_dynamite_building_bauxite_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dynamite_building_bauxite_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Dynamite (pm_dynamite_building_bauxite_mine)

Метод производства · `pm_dynamite_building_bauxite_mine` · `common/production_methods/ztr_new_production_methods.txt:5551`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dynamite.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Динамит|Динамит]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_explosives_add` = `10` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_bauxite_add` = `20` → [[tr/Товары/Bauxite|Bauxite]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Explosives (pmg_explosives_building_bauxite_mine)|Explosives (pmg_explosives_building_bauxite_mine)]]
