---
type: concept
description: "Технология «Continuous Casting» — T&R 1.13, `continuous_casting`"
project: vic3
audience: agent
source: tr
aliases: ["Continuous Casting", "continuous_casting"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: continuous_casting
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_production.txt]
---
# Continuous Casting

Технология · `continuous_casting` · `common/technology/technologies/ztr_new_production.txt:1054`

## Поля

- **era**: `era_8`
- **texture**: `gfx/interface/icons/invention_icons/continuous_casting_process.dds`
- **category**: `production`
- **unlocking_technologies**: [[tr/Технологии/Advanced Electric Arc Processes|Advanced Electric Arc Processes]]
- **modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-input-iron-mult|goods_input_iron_mult]] = `-0.05` → [[vanilla/Товары/Железо|Железо]]
  - `goods_input_copper_mult` = `-0.05` → [[tr/Товары/Медь|Медь]]
  - `goods_input_commonores_mult` = `-0.05` → [[tr/Товары/Common Ores|Common Ores]]
- **ai_weight**: скрипт, строки 1067–1069

## Ссылаются

- **Технологии** (открывает): [[tr/Технологии/Advanced Alloys|Advanced Alloys]]
