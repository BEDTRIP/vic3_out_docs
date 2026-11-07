---
type: concept
description: "Метод производства «pm_default_building_ponce_de_leon_hotel» — grey soft pop 1.13, `pm_default_building_ponce_de_leon_hotel`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_ponce_de_leon_hotel"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_ponce_de_leon_hotel
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_ponce_de_leon_hotel

Метод производства · `pm_default_building_ponce_de_leon_hotel` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2289`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_reduction_health_mult` = `-0.2`
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_clerks_add` = `1500` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
    - `building_employment_bureaucrats_add` = `500` → [[grey_soft_pop/Население/Типы/Чиновники|Чиновники]]
