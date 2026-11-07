---
type: concept
description: "Метод производства «National Park Service» — Hail Columbia 1.13, `usfp_pm_national_park_service`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["National Park Service", "usfp_pm_national_park_service"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usfp_pm_national_park_service
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# National Park Service

Метод производства · `usfp_pm_national_park_service` · `common/production_methods/usfp_production_methods.txt:144`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/usfp_pm_national_park_service.dds`
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `-150`
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `4`
    - [[vanilla/движок/Модификаторы C#^m-country-loyalism-increases-full-acceptance-mult|country_loyalism_increases_full_acceptance_mult]] = `0.02`
    - [[vanilla/движок/Модификаторы B#^m-building-group-bg-extraction-construction-efficiency-add|building_group_bg_extraction_construction_efficiency_add]] = `-0.04`
- **unlocking_technologies**: [[vanilla/Технологии/Централизованное планирование|Централизованное планирование]]

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Park Management|Park Management]]
