---
type: concept
description: "Метод производства «pm_default_building_university_of_ottawa» — grey soft pop 1.13, `pm_default_building_university_of_ottawa`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_university_of_ottawa"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_university_of_ottawa
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_university_of_ottawa

Метод производства · `pm_default_building_university_of_ottawa` · `common/production_methods/yMoG_SPA_compat_balancing.txt:1750`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-sulfur-mine-throughput-add|building_sulfur_mine_throughput_add]] = `0.3` → [[vanilla/Здания/Серные рудники|Серные рудники]]
    - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
    - [[vanilla/движок/Модификаторы B#^m-building-university-throughput-add|building_university_throughput_add]] = `0.20` → [[vanilla/Здания/Университеты|Университеты]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `2500` → [[grey_soft_pop/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `800` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
