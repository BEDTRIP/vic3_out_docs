---
type: concept
description: "Метод производства «Стандартизация методов подготовки (pm_training_streamlining_conscription)» — ваниль 1.13, `pm_training_streamlining_conscription`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартизация методов подготовки (pm_training_streamlining_conscription)", "Стандартизация методов подготовки", "pm_training_streamlining_conscription"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_training_streamlining_conscription
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Стандартизация методов подготовки (pm_training_streamlining_conscription)

Метод производства · `pm_training_streamlining_conscription` · `common/production_methods/05_military.txt:236`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/skirmish_infantry.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `85`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Военное моделирование|Военное моделирование]]
- **disallowing_laws**: [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]], [[vanilla/Законы/Воинская каста|Воинская каста]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `24`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training_conscription)|Подготовка (pmg_training_conscription)]]
