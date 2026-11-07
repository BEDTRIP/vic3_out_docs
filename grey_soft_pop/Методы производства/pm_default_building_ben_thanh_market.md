---
type: concept
description: "Метод производства «pm_default_building_ben_thanh_market» — grey soft pop 1.13, `pm_default_building_ben_thanh_market`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_ben_thanh_market"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_ben_thanh_market
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_ben_thanh_market

Метод производства · `pm_default_building_ben_thanh_market` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2903`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_tax_capacity_mult` = `0.05`
    - `state_market_access_price_impact` = `0.05`
  - **unscaled**:
    - `state_migration_pull_add` = `2`
    - `state_migration_pull_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `1500` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_capitalists_add` = `1000` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
