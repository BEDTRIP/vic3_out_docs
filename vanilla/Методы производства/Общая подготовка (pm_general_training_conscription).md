---
type: concept
description: "Метод производства «Общая подготовка (pm_general_training_conscription)» — ваниль 1.15, `pm_general_training_conscription`"
project: vic3
audience: agent
source: vanilla
aliases: ["Общая подготовка (pm_general_training_conscription)", "Общая подготовка", "pm_general_training_conscription"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_general_training_conscription
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Общая подготовка (pm_general_training_conscription)

Метод производства · `pm_general_training_conscription` · `common/production_methods/05_military.txt:187`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/cavalry.dds`
- **is_default**: `yes`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `95`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Генеральный штаб|Генеральный штаб]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `18`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training_conscription)|Подготовка (pmg_training_conscription)]]
