---
type: concept
description: "Метод производства «Включение сержантского состава (pm_nco_incorporation_conscription)» — ваниль 1.13, `pm_nco_incorporation_conscription`"
project: vic3
audience: agent
source: vanilla
aliases: ["Включение сержантского состава (pm_nco_incorporation_conscription)", "Включение сержантского состава", "pm_nco_incorporation_conscription"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nco_incorporation_conscription
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Включение сержантского состава (pm_nco_incorporation_conscription)

Метод производства · `pm_nco_incorporation_conscription` · `common/production_methods/05_military.txt:262`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/nco_incorporation.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `80`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `20`
- **unlocking_technologies**: [[vanilla/Технологии/Подготовка сержантского состава|Подготовка сержантского состава]]
- **disallowing_laws**: [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]], [[vanilla/Законы/Воинская каста|Воинская каста]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `27`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training_conscription)|Подготовка (pmg_training_conscription)]]
