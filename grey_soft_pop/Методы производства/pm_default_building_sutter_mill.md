---
type: concept
description: "Метод производства «pm_default_building_sutter_mill» — grey soft pop 1.13, `pm_default_building_sutter_mill`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_sutter_mill"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_sutter_mill
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_sutter_mill

Метод производства · `pm_default_building_sutter_mill` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2352`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_gold_mine_throughput_add` = `0.2` → [[vanilla/Здания/Золотые рудники|Золотые рудники]]
    - `state_birth_rate_mult` = `0.03`
  - **unscaled**:
    - `state_migration_pull_mult` = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_mult` = `0.03`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_shopkeepers_add` = `1000` → [[grey_soft_pop/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_engineers_add` = `500` → [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]]
