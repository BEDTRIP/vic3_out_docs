---
type: concept
description: "Метод производства «pm_default_building_erasmus_rotterdam_university» — grey soft pop 1.15, `pm_default_building_erasmus_rotterdam_university`"
project: vic3
audience: agent
source: grey_soft_pop
aliases: ["pm_default_building_erasmus_rotterdam_university"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_erasmus_rotterdam_university
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_erasmus_rotterdam_university

Метод производства · `pm_default_building_erasmus_rotterdam_university` · `common/production_methods/yMoG_SPA_compat_balancing.txt:1220`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.2` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
    - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
    - [[vanilla/движок/Модификаторы B#^m-building-university-throughput-add|building_university_throughput_add]] = `0.20` → [[vanilla/Здания/Университеты|Университеты]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `3000` → [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1000` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
