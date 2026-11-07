---
type: concept
description: "Метод производства «pm_default_building_masjed_soleyman_oil_field» — grey soft pop 1.13, `pm_default_building_masjed_soleyman_oil_field`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_masjed_soleyman_oil_field"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_masjed_soleyman_oil_field
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_masjed_soleyman_oil_field

Метод производства · `pm_default_building_masjed_soleyman_oil_field` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2331`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.30`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.12`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]]
