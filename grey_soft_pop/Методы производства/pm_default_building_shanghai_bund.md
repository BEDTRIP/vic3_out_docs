---
type: concept
description: "Метод производства «pm_default_building_shanghai_bund» — grey soft pop 1.13, `pm_default_building_shanghai_bund`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_shanghai_bund"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_shanghai_bund
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_shanghai_bund

Метод производства · `pm_default_building_shanghai_bund` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2827`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_market_access_price_impact` = `0.05`
  - **unscaled**:
    - `state_migration_pull_mult` = `0.12`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `100`
    - `state_trade_advantage_mult` = `0.1`
    - `country_bureaucracy_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `1500` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_capitalists_add` = `1000` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
