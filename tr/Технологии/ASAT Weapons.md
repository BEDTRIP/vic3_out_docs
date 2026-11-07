---
type: concept
description: "Технология «ASAT Weapons» — T&R 1.13, `anti_satellite_weapons`"
project: vic3
audience: agent
source: tr
aliases: ["ASAT Weapons", "anti_satellite_weapons"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: anti_satellite_weapons
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_military.txt]
---
# ASAT Weapons

Технология · `anti_satellite_weapons` · `common/technology/technologies/ztr_new_military.txt:782`

## Поля

- **era**: `era_8`
- **texture**: `gfx/interface/icons/invention_icons/anti_satellite_weapons.dds`
- **category**: `military`
- **modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-army-offense-mult|unit_army_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы M#^m-military-formation-organization-gain-mult|military_formation_organization_gain_mult]] = `0.1`
  - `increase_nuclear_strike_power_bool_tt` = `yes`
- **unlocking_technologies**: [[tr/Технологии/Satellites|Satellites]], [[tr/Технологии/ECM|ECM]]
- **ai_weight**: скрипт, строки 798–806

## Ссылаются

- **Технологии** (открывает): [[tr/Технологии/Electronic Warfare|Electronic Warfare]]
