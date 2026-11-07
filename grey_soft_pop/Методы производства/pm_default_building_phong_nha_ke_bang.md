---
type: concept
description: "Метод производства «pm_default_building_phong_nha_ke_bang» — grey soft pop 1.13, `pm_default_building_phong_nha_ke_bang`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_phong_nha_ke_bang"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_phong_nha_ke_bang
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_phong_nha_ke_bang

Метод производства · `pm_default_building_phong_nha_ke_bang` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2509`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `50`
    - [[vanilla/движок/Модификаторы C#^m-country-influence-add|country_influence_add]] = `200`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `0.2`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `1000` → [[grey_soft_pop/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
