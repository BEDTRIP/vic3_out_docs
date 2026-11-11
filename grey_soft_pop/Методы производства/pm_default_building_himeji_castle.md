---
type: concept
description: "Метод производства «pm_default_building_himeji_castle» — grey soft pop 1.15, `pm_default_building_himeji_castle`"
project: vic3
audience: agent
source: grey_soft_pop
aliases: ["pm_default_building_himeji_castle"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_himeji_castle
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_himeji_castle

Метод производства · `pm_default_building_himeji_castle` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2459`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `40`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-government-administration-throughput-add|building_government_administration_throughput_add]] = `0.1` → [[vanilla/Здания/Правительственные ведомства|Правительственные ведомства]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `800` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
