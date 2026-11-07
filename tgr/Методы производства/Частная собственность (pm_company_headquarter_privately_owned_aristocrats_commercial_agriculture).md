---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)» — TGR 1.13, `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture`"
project: vic3
source: tgr
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)", "Частная собственность", "pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)

Метод производства · `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:243`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `aristocrat_owned`
- **unlocking_laws**: [[tgr/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]]
- **disallowing_laws**: [[tgr/Законы/Командная экономика|Командная экономика]], [[tgr/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `15` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_aristocrats_add` = `10` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_clerks_add` = `25` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_aristocrats_shares_add` = `10`
- **state_modifiers**:
  - **level_scaled**:
    - `state_weekly_trades_add` = `0.5`
    - `state_trade_capacity_add` = `1`
    - `state_tax_capacity_add` = `0.25`
