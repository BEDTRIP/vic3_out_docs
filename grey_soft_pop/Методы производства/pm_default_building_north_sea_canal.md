---
type: concept
description: "Метод производства «pm_default_building_north_sea_canal» — grey soft pop 1.13, `pm_default_building_north_sea_canal`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_north_sea_canal"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_north_sea_canal
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_north_sea_canal

Метод производства · `pm_default_building_north_sea_canal` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2621`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**: пусто
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `100`
    - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
    - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-mult|country_bureaucracy_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]]
