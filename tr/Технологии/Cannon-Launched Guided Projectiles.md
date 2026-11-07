---
type: concept
description: "Технология «Cannon-Launched Guided Projectiles» — T&R 1.13, `cannon_launched_guided_projectiles`"
project: vic3
source: tr
aliases: ["Cannon-Launched Guided Projectiles", "cannon_launched_guided_projectiles"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: cannon_launched_guided_projectiles
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_military.txt]
---
# Cannon-Launched Guided Projectiles

Технология · `cannon_launched_guided_projectiles` · `common/technology/technologies/ztr_new_military.txt:1146`

## Поля

- **era**: `era_9`
- **texture**: `gfx/interface/icons/invention_icons/cannon_launched_guided_projectiles.dds`
- **category**: `military`
- **modifier**:
  - `unit_combat_unit_type_mechanized_infantry_offense_mult` = `0.1`
  - `unit_combat_unit_type_modern_mechanized_infantry_offense_mult` = `0.15`
  - `unit_combat_unit_type_advanced_mechanized_infantry_offense_mult` = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-military-wages-mult|country_military_wages_mult]] = `0.25`
- **unlocking_technologies**: [[tr/Технологии/Composite Armor|Composite Armor]], [[tr/Технологии/High-Performance War Apparel|High-Performance War Apparel]]
- **ai_weight**: скрипт, строки 1163–1165

## Ссылаются

- **Методы производства** (открывает): [[tr/Методы производства/Launched Guided Projectiles|Launched Guided Projectiles]]
