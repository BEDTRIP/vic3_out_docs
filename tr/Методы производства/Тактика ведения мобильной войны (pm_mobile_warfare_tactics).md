---
type: concept
description: "Метод производства «Тактика ведения мобильной войны (pm_mobile_warfare_tactics)» — T&R 1.13, `pm_mobile_warfare_tactics`"
project: vic3
source: tr
aliases: ["Тактика ведения мобильной войны (pm_mobile_warfare_tactics)", "Mobile Warfare Tactics", "pm_mobile_warfare_tactics"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mobile_warfare_tactics
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Тактика ведения мобильной войны (pm_mobile_warfare_tactics)]]"
---
# Тактика ведения мобильной войны (pm_mobile_warfare_tactics)

Метод производства · `pm_mobile_warfare_tactics` · `common/production_methods/ztr_vanilla_production_methods.txt:1592` · заменяет запись ваниль (`REPLACE:`)

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
    - `building_training_rate_add` = `50`
  - **level_scaled**:
    - `building_training_rate_add` = `24`
