---
type: concept
description: "Метод производства «Atomic Bomb» — T&R 1.13, `pm_atomic_bomb`"
project: vic3
source: tr
aliases: ["Atomic Bomb", "pm_atomic_bomb"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_atomic_bomb
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Atomic Bomb

Метод производства · `pm_atomic_bomb` · `common/production_methods/ztr_military_production_methods.txt:442`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_atomic_bomb.dds`
- **unlocking_technologies**: [[tr/Технологии/Atomic Bomb|Atomic Bomb]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_good_uranium_add` = `40` → [[tr/Товары/Uranium|Uranium]]
    - `goods_input_steel_add` = `20` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_explosives_add` = `20` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_water_add` = `20` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - `building_employment_academics_add` = `7500` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_officers_add` = `2500` → [[vanilla/Население/Типы/Офицеры|Офицеры]]
- **timed_modifiers**: `pm_offense_defense_readjustment`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Nuclear Weapon Type|Nuclear Weapon Type]]
