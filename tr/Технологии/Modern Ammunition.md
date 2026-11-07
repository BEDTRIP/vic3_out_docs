---
type: concept
description: "Технология «Modern Ammunition» — T&R 1.13, `precision_ammunition`"
project: vic3
source: tr
aliases: ["Modern Ammunition", "precision_ammunition"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: precision_ammunition
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_military.txt]
---
# Modern Ammunition

Технология · `precision_ammunition` · `common/technology/technologies/ztr_new_military.txt:627`

## Поля

- **era**: `era_7`
- **texture**: `gfx/interface/icons/invention_icons/precision_ammunition.dds`
- **category**: `military`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-military-wages-mult|country_military_wages_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы U#^m-unit-army-offense-mult|unit_army_offense_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-artillery-foundry-throughput-add|building_artillery_foundry_throughput_add]] = `0.05` → [[tr/Здания/Артиллерийские заводы|Артиллерийские заводы]]
  - [[vanilla/движок/Модификаторы U#^m-unit-kill-rate-add|unit_kill_rate_add]] = `0.05`
- **unlocking_technologies**: [[tr/Технологии/Assault Rifle|Assault Rifle]]
- **ai_weight**: скрипт, строки 644–652

## Ссылаются

- **Методы производства** (открывает): [[tr/Методы производства/Precised Shells|Precised Shells]]
- **Технологии** (открывает): [[tr/Технологии/Laser-Guided Weapons|Laser-Guided Weapons]]
