---
type: concept
description: "Метод производства «pm_default_building_uffizi» — grey soft pop 1.13, `pm_default_building_uffizi`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_uffizi"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_uffizi
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_uffizi

Метод производства · `pm_default_building_uffizi` · `common/production_methods/yMoG_SPA_compat_balancing.txt:3080`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pop_qualifications_mult` = `0.2`
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_aristocrats_add` = `100` → [[grey_soft_pop/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_bureaucrats_add` = `100` → [[grey_soft_pop/Население/Типы/Чиновники|Чиновники]]
