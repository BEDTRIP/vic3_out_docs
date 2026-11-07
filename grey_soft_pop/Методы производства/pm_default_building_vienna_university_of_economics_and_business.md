---
type: concept
description: "Метод производства «pm_default_building_vienna_university_of_economics_and_business» — grey soft pop 1.13, `pm_default_building_vienna_university_of_economics_and_business`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_vienna_university_of_economics_and_business"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_vienna_university_of_economics_and_business
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_vienna_university_of_economics_and_business

Метод производства · `pm_default_building_vienna_university_of_economics_and_business` · `common/production_methods/yMoG_SPA_compat_balancing.txt:1496`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_art_academy_throughput_add` = `0.2` → [[vanilla/Здания/Академии искусств|Академии искусств]]
    - `state_education_access_wealth_add` = `0.005`
    - `building_university_throughput_add` = `0.20` → [[vanilla/Здания/Университеты|Университеты]]
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_academics_add` = `2000` → [[grey_soft_pop/Население/Типы/Учёные|Учёные]]
    - `building_employment_clerks_add` = `700` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
