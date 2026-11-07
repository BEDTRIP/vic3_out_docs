---
type: concept
description: "Метод производства «Nitroglycerin (pm_nitroglycerin_building_bauxite_mine)» — T&R 1.13, `pm_nitroglycerin_building_bauxite_mine`"
project: vic3
source: tr
aliases: ["Nitroglycerin (pm_nitroglycerin_building_bauxite_mine)", "Nitroglycerin", "pm_nitroglycerin_building_bauxite_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nitroglycerin_building_bauxite_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Nitroglycerin (pm_nitroglycerin_building_bauxite_mine)

Метод производства · `pm_nitroglycerin_building_bauxite_mine` · `common/production_methods/ztr_new_production_methods.txt:5517`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/nitroglycerin.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Нитроглицерин|Нитроглицерин]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_explosives_add` = `5` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_output_bauxite_add` = `12` → [[tr/Товары/Bauxite|Bauxite]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.3`
    - `building_machinists_mortality_mult` = `0.2`
    - `building_engineers_mortality_mult` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Explosives (pmg_explosives_building_bauxite_mine)|Explosives (pmg_explosives_building_bauxite_mine)]]
