---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)» — TGR 1.13, `pm_company_headquarter_privately_owned_bureaucrats`"
project: vic3
source: tgr
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)", "Частная собственность", "pm_company_headquarter_privately_owned_bureaucrats"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_bureaucrats
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)

Метод производства · `pm_company_headquarter_privately_owned_bureaucrats` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:315`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `bureaucrat_owned`
- **disallowing_laws**: [[tgr/Законы/Командная экономика|Командная экономика]], [[tgr/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `25` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `15` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-bureaucrats-shares-add|building_bureaucrats_shares_add]] = `5`
    - [[vanilla/движок/Модификаторы B#^m-building-company-government-dividends-add|building_company_government_dividends_add]] = `0.25`
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-weekly-trades-add|state_weekly_trades_add]] = `0.5`
    - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-add|state_trade_capacity_add]] = `1`
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `0.25`
