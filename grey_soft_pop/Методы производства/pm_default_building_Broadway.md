---
type: concept
description: "Метод производства «pm_default_building_Broadway» — grey soft pop 1.13, `pm_default_building_Broadway`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_Broadway"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_Broadway
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_Broadway

Метод производства · `pm_default_building_Broadway` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2650`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**: пусто
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.7`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `60`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `1000` → [[grey_soft_pop/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `100` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
