---
type: concept
description: "Метод производства «pm_default_building_brooklyn_bridge» — grey soft pop 1.15, `pm_default_building_brooklyn_bridge`"
project: vic3
audience: agent
source: grey_soft_pop
aliases: ["pm_default_building_brooklyn_bridge"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_brooklyn_bridge
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_brooklyn_bridge

Метод производства · `pm_default_building_brooklyn_bridge` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2952`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `100`
    - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.2` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1800` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[grey_soft_pop/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `200` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
