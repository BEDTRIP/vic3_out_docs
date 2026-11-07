---
type: concept
description: "Метод производства «Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)» — T&R 1.13, `pm_mobile_warfare_tactics_conscription`"
project: vic3
audience: agent
source: tr
aliases: ["Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)", "Тактика ведения мобильной войны", "pm_mobile_warfare_tactics_conscription"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mobile_warfare_tactics_conscription
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)]]"
---
# Тактика ведения мобильной войны (pm_mobile_warfare_tactics_conscription)

Метод производства · `pm_mobile_warfare_tactics_conscription` · `common/production_methods/ztr_vanilla_production_methods.txt:1612` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **unlocking_technologies**: изменено
- **disallowing_laws**: убрано

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/motorised_logistics.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `75`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `25`
- **unlocking_technologies**: [[tr/Технологии/Blitzkrieg|Blitzkrieg]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `30`
