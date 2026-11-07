---
type: concept
description: "Метод производства «Тактика ведения мобильной войны (pm_mobile_warfare_tactics)» — ваниль 1.13, `pm_mobile_warfare_tactics`"
project: vic3
source: vanilla
aliases: ["Тактика ведения мобильной войны (pm_mobile_warfare_tactics)", "Mobile Warfare Tactics", "pm_mobile_warfare_tactics"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mobile_warfare_tactics
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Тактика ведения мобильной войны (pm_mobile_warfare_tactics)

Метод производства · `pm_mobile_warfare_tactics` · `common/production_methods/05_military.txt:120`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/motorised_logistics.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `75`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `25`
- **disallowing_laws**: [[vanilla/Законы/Воинская каста|Воинская каста]]
- **unlocking_technologies**: [[vanilla/Технологии/Подвижная броня|Подвижная броня]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `24`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training)|Подготовка (pmg_training)]]
