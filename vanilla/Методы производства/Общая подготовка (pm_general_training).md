---
type: concept
description: "Метод производства «Общая подготовка (pm_general_training)» — ваниль 1.13, `pm_general_training`"
project: vic3
source: vanilla
aliases: ["Общая подготовка (pm_general_training)", "General Training", "pm_general_training"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_general_training
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Общая подготовка (pm_general_training)

Метод производства · `pm_general_training` · `common/production_methods/05_military.txt:23`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/cavalry.dds`
- **is_default**: `yes`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `95`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `5`
- **disallowing_laws**: [[vanilla/Законы/Воинская каста|Воинская каста]]
- **unlocking_technologies**: [[vanilla/Технологии/Генеральный штаб|Генеральный штаб]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `15`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training)|Подготовка (pmg_training)]]
