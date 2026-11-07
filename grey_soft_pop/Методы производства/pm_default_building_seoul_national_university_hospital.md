---
type: concept
description: "Метод производства «pm_default_building_seoul_national_university_hospital» — grey soft pop 1.13, `pm_default_building_seoul_national_university_hospital`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_seoul_national_university_hospital"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_seoul_national_university_hospital
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_seoul_national_university_hospital

Метод производства · `pm_default_building_seoul_national_university_hospital` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2719`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_birth_rate_mult` = `0.03`
    - `building_university_throughput_add` = `0.1` → [[vanilla/Здания/Университеты|Университеты]]
  - **unscaled**:
    - `state_migration_pull_mult` = `0.12`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_weekly_innovation_max_add` = `20`
    - `country_weekly_innovation_add` = `50`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_academics_add` = `2000` → [[grey_soft_pop/Население/Типы/Учёные|Учёные]]
