---
type: concept
description: "Метод производства «Network-Centric Warfare (pm_network_centric_warfare)» — T&R 1.13, `pm_network_centric_warfare`"
project: vic3
audience: agent
source: tr
aliases: ["Network-Centric Warfare (pm_network_centric_warfare)", "Network-Centric Warfare", "pm_network_centric_warfare"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_network_centric_warfare
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Network-Centric Warfare (pm_network_centric_warfare)

Метод производства · `pm_network_centric_warfare` · `common/production_methods/ztr_military_production_methods.txt:357`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/network_centric_warfare.dds`
- **profession_ratio**:
  - [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]] = `70`
  - [[vanilla/Население/Типы/Офицеры|Офицеры]] = `30`
- **unlocking_technologies**: [[tr/Технологии/Network-Centric Warfare|Network-Centric Warfare]]
- **disallowing_laws**: [[vanilla/Законы/Воинская каста|Воинская каста]]
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `50`
    - [[vanilla/движок/Модификаторы M#^m-military-formation-organization-gain-mult|military_formation_organization_gain_mult]] = `0.1`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-training-rate-add|building_training_rate_add]] = `27`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Подготовка (pmg_training)|Подготовка (pmg_training)]]
