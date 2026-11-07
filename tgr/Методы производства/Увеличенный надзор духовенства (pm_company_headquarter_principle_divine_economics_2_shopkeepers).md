---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)» — TGR 1.13, `pm_company_headquarter_principle_divine_economics_2_shopkeepers`"
project: vic3
source: tgr
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_shopkeepers"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_shopkeepers
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)]]"
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_shopkeepers` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:503`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `shopkeeper_owned`
- **disallowing_laws**: [[tgr/Законы/Командная экономика|Командная экономика]], [[tgr/Законы/Кооперативное владение|Кооперативное владение]]
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_shopkeepers_add` = `15` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clergymen_add` = `25` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_shopkeepers_shares_add` = `5`
    - `building_clergymen_shares_add` = `2`
    - `building_company_worker_dividends_add` = `0.25`
- **state_modifiers**:
  - **level_scaled**:
    - `state_weekly_trades_add` = `0.5`
    - `state_trade_capacity_add` = `1`
    - `state_tax_capacity_add` = `0.25`
