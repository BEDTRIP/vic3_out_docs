---
type: concept
description: "Метод производства «pm_default_building_jameh_mosque» — grey soft pop 1.13, `pm_default_building_jameh_mosque`"
project: vic3
audience: agent
source: grey_soft_pop
aliases: ["pm_default_building_jameh_mosque"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_jameh_mosque
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_jameh_mosque

Метод производства · `pm_default_building_jameh_mosque` · `common/production_methods/yMoG_SPA_compat_balancing.txt:3102`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**: пусто
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pol-str-mult|interest_group_ig_devout_pol_str_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `1000` → [[grey_soft_pop/Население/Типы/Священнослужители|Священнослужители]]
