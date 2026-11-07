---
type: concept
description: "Метод производства «Отсутствие организованной подготовки (pm_no_organization)» — ваниль 1.13, `pm_no_organization`"
project: vic3
audience: agent
source: vanilla
aliases: ["Отсутствие организованной подготовки (pm_no_organization)", "No Organized Training", "pm_no_organization"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_no_organization
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Отсутствие организованной подготовки (pm_no_organization)

Метод производства · `pm_no_organization` · `common/production_methods/05_military.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/no_specialists.dds`
- **is_default**: `yes`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `97`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `3`
- **disallowing_laws**: [[vanilla/Законы/Воинская каста|Воинская каста]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `8`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training)|Подготовка (pmg_training)]]
