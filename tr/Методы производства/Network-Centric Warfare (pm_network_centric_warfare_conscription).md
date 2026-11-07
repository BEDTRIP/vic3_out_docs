---
type: concept
description: "Метод производства «Network-Centric Warfare (pm_network_centric_warfare_conscription)» — T&R 1.13, `pm_network_centric_warfare_conscription`"
project: vic3
source: tr
aliases: ["Network-Centric Warfare (pm_network_centric_warfare_conscription)", "Network-Centric Warfare", "pm_network_centric_warfare_conscription"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_network_centric_warfare_conscription
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Network-Centric Warfare (pm_network_centric_warfare_conscription)

Метод производства · `pm_network_centric_warfare_conscription` · `common/production_methods/ztr_military_production_methods.txt:383`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/network_centric_warfare.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `70`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `30`
- **unlocking_technologies**: [[tr/Технологии/Network-Centric Warfare|Network-Centric Warfare]]
- **disallowing_laws**: [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]], [[vanilla/Законы/Воинская каста|Воинская каста]]
- **building_modifiers**:
  - **unscaled**:
    - `building_training_rate_add` = `50`
    - `military_formation_organization_gain_mult` = `0.1`
  - **level_scaled**:
    - `building_training_rate_add` = `33`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Подготовка (pmg_training_conscription)|Подготовка (pmg_training_conscription)]]
