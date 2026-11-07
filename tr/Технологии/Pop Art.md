---
type: concept
description: "Технология «Pop Art» — T&R 1.13, `pop_art`"
project: vic3
audience: agent
source: tr
aliases: ["Pop Art", "pop_art"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pop_art
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_society.txt]
---
# Pop Art

Технология · `pop_art` · `common/technology/technologies/ztr_new_society.txt:678`

## Поля

- **era**: `era_7`
- **texture**: `gfx/interface/icons/invention_icons/pop_art.dds`
- **category**: `society`
- **unlocking_technologies**: [[tr/Технологии/Telecommunications|Telecommunications]], [[tr/Технологии/Counterculture|Counterculture]]
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - `building_manzoni_publishing_industry_throughput_add` = `0.05` → [[tr/Здания/Media Industries|Media Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-decree-cost-mult|state_decree_cost_mult]] = `-0.1`
- **ai_weight**: скрипт, строки 694–696

## Ссылаются

- **Методы производства** (открывает): [[tr/Методы производства/Modern Dance|Modern Dance]], [[tr/Методы производства/Pop Art|Pop Art]]
- **Технологии** (открывает): [[tr/Технологии/Transnational Activism|Transnational Activism]]
