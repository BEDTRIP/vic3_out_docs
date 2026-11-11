---
type: concept
description: "Метод производства «Обучение современной тактике (pm_advanced_tactics_training)» — ваниль 1.15, `pm_advanced_tactics_training`"
project: vic3
audience: agent
source: vanilla
aliases: ["Обучение современной тактике (pm_advanced_tactics_training)", "Advanced Tactics Training", "pm_advanced_tactics_training"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_tactics_training
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Обучение современной тактике (pm_advanced_tactics_training)

Метод производства · `pm_advanced_tactics_training` · `common/production_methods/05_military.txt:48`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/squad_infantry.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `90`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `10`
- **disallowing_laws**: [[vanilla/Законы/Воинская каста|Воинская каста]]
- **unlocking_technologies**: [[vanilla/Технологии/Военная статистика|Военная статистика]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `17`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training)|Подготовка (pmg_training)]]
