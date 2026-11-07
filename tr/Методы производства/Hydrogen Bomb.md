---
type: concept
description: "Метод производства «Hydrogen Bomb» — T&R 1.13, `pm_hydrogen_bomb`"
project: vic3
audience: agent
source: tr
aliases: ["Hydrogen Bomb", "pm_hydrogen_bomb"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hydrogen_bomb
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Hydrogen Bomb

Метод производства · `pm_hydrogen_bomb` · `common/production_methods/ztr_military_production_methods.txt:474`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_hydrogen_bomb.dds`
- **unlocking_technologies**: [[tr/Технологии/Hydrogen bomb|Hydrogen bomb]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_advancedores_add` = `20` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_alloys_add` = `20` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_robotics_add` = `10` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `10` → [[tr/Товары/Processors|Processors]]
    - `goods_input_water_add` = `40` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `7500` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-officers-add|building_employment_officers_add]] = `2500` → [[vanilla/Население/Типы/Офицеры|Офицеры]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-from-army-power-projection-mult|country_prestige_from_army_power_projection_mult]] = `0.1`
- **timed_modifiers**: `pm_offense_defense_readjustment`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Nuclear Weapon Type|Nuclear Weapon Type]]
