---
type: concept
description: "Метод производства «pm_default_building_hsbc_building» — grey soft pop 1.13, `pm_default_building_hsbc_building`"
project: vic3
source: grey_soft_pop
aliases: ["pm_default_building_hsbc_building"]
tags: [grey_soft_pop, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_hsbc_building
paths: [grey_add_alot_of_things/_grey_soft_pop/common/production_methods/yMoG_SPA_compat_balancing.txt]
---
# pm_default_building_hsbc_building

Метод производства · `pm_default_building_hsbc_building` · `common/production_methods/yMoG_SPA_compat_balancing.txt:2381`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_trade_center_throughput_add` = `0.2` → [[vanilla/Здания/Торговые центры|Торговые центры]]
    - `state_tax_capacity_mult` = `0.05`
    - `state_radicals_and_loyalists_from_sol_change_mult` = `0.05`
    - `building_nationalization_investment_return_add` = `0.05`
    - `state_shopkeepers_investment_pool_efficiency_mult` = `0.05`
    - `state_aristocrats_investment_pool_efficiency_mult` = `0.05`
    - `state_capitalists_investment_pool_efficiency_mult` = `0.05`
    - `state_farmers_investment_pool_efficiency_mult` = `0.05`
    - `state_clergymen_investment_pool_efficiency_mult` = `0.05`
  - **unscaled**:
    - `state_migration_pull_add` = `2`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[grey_soft_pop/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_aristocrats_add` = `500` → [[grey_soft_pop/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_capitalists_add` = `500` → [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_farmers_add` = `500` → [[grey_soft_pop/Население/Типы/Фермеры|Фермеры]]
    - `building_employment_clergymen_add` = `500` → [[grey_soft_pop/Население/Типы/Священнослужители|Священнослужители]]
