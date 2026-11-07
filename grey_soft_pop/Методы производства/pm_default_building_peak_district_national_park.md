---
type: concept
description: "Метод производства «pm_default_building_peak_district_national_park» — grey soft pop 1.13, `pm_default_building_peak_district_national_park`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_peak_district_national_park"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_peak_district_national_park
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_peak_district_national_park

Метод производства · `pm_default_building_peak_district_national_park` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2055`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_reduction_health_mult` = `-0.20`
    - `state_pollution_generation_add` = `-100`
  - **unscaled**:
    - `state_migration_pull_add` = `2`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `500` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
