---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)» — TGR 1.15, `pm_company_headquarter_principle_divine_economics_2_academics`"
project: vic3
audience: agent
source: tgr
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_academics"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_academics
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)]]"
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_academics` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:583`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `academic_owned`
- **disallowing_laws**: [[tgr/Законы/Командная экономика|Командная экономика]], [[tgr/Законы/Кооперативное владение|Кооперативное владение]]
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `15` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `25` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-academics-shares-add|building_academics_shares_add]] = `5`
    - [[vanilla/движок/Модификаторы B#^m-building-clergymen-shares-add|building_clergymen_shares_add]] = `2`
    - [[vanilla/движок/Модификаторы B#^m-building-company-worker-dividends-add|building_company_worker_dividends_add]] = `0.25`
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-weekly-trades-add|state_weekly_trades_add]] = `0.5`
    - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-add|state_trade_capacity_add]] = `1`
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `0.25`
