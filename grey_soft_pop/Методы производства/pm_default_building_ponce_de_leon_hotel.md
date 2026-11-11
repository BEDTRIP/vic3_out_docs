---
type: concept
description: "Метод производства «pm_default_building_ponce_de_leon_hotel» — grey soft pop 1.15, `pm_default_building_ponce_de_leon_hotel`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.2`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1500` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `500` → [[grey_soft_pop/Население/Типы/Чиновники|Чиновники]]
