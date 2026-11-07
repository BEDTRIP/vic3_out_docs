---
type: concept
description: "Метод производства «pm_default_building_mysore_palace» — grey soft pop 1.13, `pm_default_building_mysore_palace`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_mysore_palace"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_mysore_palace
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_mysore_palace

Метод производства · `pm_default_building_mysore_palace` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2262`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_reduction_health_mult` = `-0.2`
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `50`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_clerks_add` = `1500` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
    - `building_employment_bureaucrats_add` = `500` → [[grey_soft_pop/Население/Типы/Чиновники|Чиновники]]
