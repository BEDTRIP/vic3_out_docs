---
type: concept
description: "Метод производства «pm_default_building_three_gorges_dam» — grey soft pop 1.13, `pm_default_building_three_gorges_dam`"
project: vic3
audience: agent
source: grey_soft_pop
aliases: ["pm_default_building_three_gorges_dam"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_three_gorges_dam
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_three_gorges_dam

Метод производства · `pm_default_building_three_gorges_dam` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2879`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-mult|state_tax_capacity_mult]] = `0.05`
    - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.2` → [[vanilla/Здания/Электрозаводы|Электрозаводы]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `500` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `1000` → [[vanilla/Товары/Электричество|Электричество]]
