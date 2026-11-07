---
type: concept
description: "Метод производства «Отсутствие организованной подготовки (pm_no_organization_conscription)» — ваниль 1.13, `pm_no_organization_conscription`"
project: vic3
audience: agent
source: vanilla
aliases: ["Отсутствие организованной подготовки (pm_no_organization_conscription)", "Отсутствие организованной подготовки", "pm_no_organization_conscription"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_no_organization_conscription
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Отсутствие организованной подготовки (pm_no_organization_conscription)

Метод производства · `pm_no_organization_conscription` · `common/production_methods/05_military.txt:167`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/no_specialists.dds`
- **is_default**: `yes`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `97`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `3`
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training_conscription)|Подготовка (pmg_training_conscription)]]
