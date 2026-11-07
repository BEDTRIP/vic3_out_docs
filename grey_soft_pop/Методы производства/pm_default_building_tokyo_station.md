---
type: concept
description: "Метод производства «pm_default_building_tokyo_station» — grey soft pop 1.13, `pm_default_building_tokyo_station`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_tokyo_station"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_tokyo_station
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_tokyo_station

Метод производства · `pm_default_building_tokyo_station` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2697`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_market_access_price_impact` = `0.05`
    - `building_railway_throughput_add` = `0.2` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `3000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_engineers_add` = `1000` → [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]]
