---
type: concept
description: "Метод производства «pm_default_building_leaning_tower_of_pisa» — grey soft pop 1.13, `pm_default_building_leaning_tower_of_pisa`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_leaning_tower_of_pisa"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_leaning_tower_of_pisa
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_leaning_tower_of_pisa

Метод производства · `pm_default_building_leaning_tower_of_pisa` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2561`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `50`
- **state_modifiers**:
  - **workforce_scaled**: пусто
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - `interest_group_ig_devout_pol_str_mult` = `0.05`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
