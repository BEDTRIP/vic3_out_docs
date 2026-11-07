---
type: concept
description: "Технология «Modern Mechanized Infantry» — T&R 1.13, `mechanized_infantry`"
project: vic3
audience: agent
source: tr
aliases: ["Modern Mechanized Infantry", "mechanized_infantry"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: mechanized_infantry
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_military.txt]
---
# Modern Mechanized Infantry

Технология · `mechanized_infantry` · `common/technology/technologies/ztr_new_military.txt:70`

## Поля

- **era**: `era_6`
- **texture**: `gfx/interface/icons/invention_icons/mechanized_infantry.dds`
- **category**: `military`
- **modifier**:
  - [[vanilla/движок/Модификаторы M#^m-military-formation-mobilization-speed-mult|military_formation_mobilization_speed_mult]] = `0.2`
  - `unit_combat_unit_type_self_propelled_artillery_offense_mult` = `0.05`
  - `unit_advancement_speed_mult` = `0.1`
  - [[vanilla/движок/Модификаторы M#^m-military-formation-attrition-risk-mult|military_formation_attrition_risk_mult]] = `-0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-military-wages-mult|country_military_wages_mult]] = `0.25`
- **unlocking_technologies**: [[vanilla/Технологии/Подвижная броня|Подвижная броня]]
- **ai_weight**: скрипт, строки 84–92

## Ссылаются

- **Технологии** (открывает): [[tr/Технологии/Blitzkrieg|Blitzkrieg]], [[tr/Технологии/Rocket Artillery|Rocket Artillery]]
