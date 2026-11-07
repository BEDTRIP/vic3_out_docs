---
type: concept
description: "Метод производства «pm_default_building_hollywood» — grey soft pop 1.13, `pm_default_building_hollywood`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_hollywood"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_hollywood
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_hollywood

Метод производства · `pm_default_building_hollywood` · `common/production_methods/yMoG_SPA_compat_balancing.txt:3053`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_art_academy_throughput_add` = `0.2` → [[vanilla/Здания/Академии искусств|Академии искусств]]
  - **unscaled**:
    - `state_migration_pull_mult` = `0.15`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `100`
    - `country_influence_add` = `200`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_clerks_add` = `1000` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
    - `building_employment_capitalists_add` = `1000` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
