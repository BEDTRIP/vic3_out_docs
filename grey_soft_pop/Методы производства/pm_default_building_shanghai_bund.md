---
type: concept
description: "Метод производства «pm_default_building_shanghai_bund» — grey soft pop 1.13, `pm_default_building_shanghai_bund`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.05`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.12`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `100`
    - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
    - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-mult|country_bureaucracy_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `1000` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
