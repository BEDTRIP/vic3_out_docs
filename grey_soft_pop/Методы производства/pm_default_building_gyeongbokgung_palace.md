---
type: concept
description: "Метод производства «pm_default_building_gyeongbokgung_palace» — grey soft pop 1.13, `pm_default_building_gyeongbokgung_palace`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_gyeongbokgung_palace"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_gyeongbokgung_palace
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_gyeongbokgung_palace

Метод производства · `pm_default_building_gyeongbokgung_palace` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2434`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `50`
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_government_administration_throughput_add` = `0.2` → [[vanilla/Здания/Правительственные ведомства|Правительственные ведомства]]
  - **unscaled**:
    - `state_migration_pull_mult` = `0.05`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]]
