---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_kaiserforum_3)» — ваниль 1.13, `pm_default_building_kaiserforum_3`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартное производство (pm_default_building_kaiserforum_3)", "Default Production", "pm_default_building_kaiserforum_3"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_kaiserforum_3
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_kaiserforum_3)

Метод производства · `pm_default_building_kaiserforum_3` · `common/production_methods/08_monuments.txt:506`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-headofstate-add|country_legitimacy_headofstate_add]] = `5`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-government-administration-throughput-add|building_government_administration_throughput_add]] = `0.2` → [[vanilla/Здания/Правительственные ведомства|Правительственные ведомства]]
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.5`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `100` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `100` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `200` → [[vanilla/Население/Типы/Чиновники|Чиновники]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_kaiserforum_3)|Основа (pmg_base_building_kaiserforum_3)]]
