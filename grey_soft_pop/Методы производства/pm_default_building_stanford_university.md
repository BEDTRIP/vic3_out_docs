---
type: concept
description: "Метод производства «pm_default_building_stanford_university» — grey soft pop 1.13, `pm_default_building_stanford_university`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_stanford_university"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_stanford_university
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_stanford_university

Метод производства · `pm_default_building_stanford_university` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2745`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.2` → [[vanilla/Здания/Электрозаводы|Электрозаводы]]
    - [[vanilla/движок/Модификаторы B#^m-building-university-throughput-add|building_university_throughput_add]] = `0.2` → [[vanilla/Здания/Университеты|Университеты]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.11`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-add|country_weekly_innovation_add]] = `30`
    - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `20`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `2500` → [[grey_soft_pop/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[grey_soft_pop/Население/Типы/Служащие|Служащие]]
