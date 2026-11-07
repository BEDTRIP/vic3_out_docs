---
type: concept
description: "Метод производства «pm_default_building_sacramento_port» — grey soft pop 1.13, `pm_default_building_sacramento_port`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_sacramento_port"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_sacramento_port
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_sacramento_port

Метод производства · `pm_default_building_sacramento_port` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2592`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**: пусто
  - **unscaled**:
    - `state_migration_pull_add` = `2`
    - `state_migration_pull_mult` = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `100`
    - `state_trade_advantage_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `3500` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_engineers_add` = `1500` → [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]]
