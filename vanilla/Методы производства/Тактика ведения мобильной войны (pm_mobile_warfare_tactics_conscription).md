---
type: concept
description: "Метод производства «Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)» — ваниль 1.13, `pm_mobile_warfare_tactics_conscription`"
project: vic3
audience: agent
source: vanilla
aliases: ["Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)", "Тактика ведения мобильной войны", "pm_mobile_warfare_tactics_conscription"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mobile_warfare_tactics_conscription
paths: [.vanillaVIC3/common/production_methods/05_military.txt]
---
# Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)

Метод производства · `pm_mobile_warfare_tactics_conscription` · `common/production_methods/05_military.txt:288`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/motorised_logistics.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `75`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `25`
- **unlocking_technologies**: [[vanilla/Технологии/Подвижная броня|Подвижная броня]]
- **disallowing_laws**: [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]], [[vanilla/Законы/Воинская каста|Воинская каста]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `30`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Подготовка (pmg_training_conscription)|Подготовка (pmg_training_conscription)]]
