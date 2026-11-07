---
type: concept
description: "Метод производства «Стандартизация методов подготовки (pm_training_streamlining)» — ваниль 1.13, `pm_training_streamlining`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартизация методов подготовки (pm_training_streamlining)", "Training Method Streamlining", "pm_training_streamlining"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_training_streamlining
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Стандартизация методов подготовки (pm_training_streamlining)

Метод производства · `pm_training_streamlining` · `common/production_methods/05_military.txt:72`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/skirmish_infantry.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `85`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `15`
- **disallowing_laws**: [[vanilla/Законы/Воинская каста|Воинская каста]]
- **unlocking_technologies**: [[vanilla/Технологии/Военное моделирование|Военное моделирование]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `19`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training)|Подготовка (pmg_training)]]
