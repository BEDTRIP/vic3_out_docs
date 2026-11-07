---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_victoria_terminus)» — ваниль 1.13, `pm_default_building_victoria_terminus`"
project: vic3
source: vanilla
aliases: ["Стандартное производство (pm_default_building_victoria_terminus)", "Default Production", "pm_default_building_victoria_terminus"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_victoria_terminus
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_victoria_terminus)

Метод производства · `pm_default_building_victoria_terminus` · `common/production_methods/08_monuments.txt:455`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `50`
    - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.20` → [[vanilla/Здания/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `200` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_victoria_terminus)|Основа (pmg_base_building_victoria_terminus)]]
