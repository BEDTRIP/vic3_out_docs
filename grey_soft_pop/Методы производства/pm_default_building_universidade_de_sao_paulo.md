---
type: concept
description: "Метод производства «pm_default_building_universidade_de_sao_paulo» — grey soft pop 1.13, `pm_default_building_universidade_de_sao_paulo`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_universidade_de_sao_paulo"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_universidade_de_sao_paulo
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_universidade_de_sao_paulo

Метод производства · `pm_default_building_universidade_de_sao_paulo` · `common/production_methods/yMoG_SPA_compat_balancing.txt:1797`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_rubber_plantation_throughput_add` = `0.3` → [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]]
    - `state_education_access_wealth_add` = `0.005`
    - `building_university_throughput_add` = `0.20` → [[vanilla/Здания/Университеты|Университеты]]
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_academics_add` = `3000` → [[grey_soft_pop/Население/Типы/Учёные|Учёные]]
    - `building_employment_clerks_add` = `1000` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
