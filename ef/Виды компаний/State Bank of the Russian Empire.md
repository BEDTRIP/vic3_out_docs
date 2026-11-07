---
type: concept
description: "Вид компании «State Bank of the Russian Empire» — E&F 1.13, `company_StateBankRussianEmpire`"
project: vic3
audience: agent
source: ef
aliases: ["State Bank of the Russian Empire", "company_StateBankRussianEmpire"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_StateBankRussianEmpire
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# State Bank of the Russian Empire

Вид компании · `company_StateBankRussianEmpire` · `common/company_types/00_ef_companies.txt:2521`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Russian_EmpireBank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Bank_SBRE`
- **preferred_headquarters**: `STATE_INGRIA`, `STATE_MOSCOW`
- **possible_prestige_goods**: `agricultural_stock_rus`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Ржаные поля|Ржаные поля]], [[ef/Здания/Пшеничные поля|Пшеничные поля]], [[ef/Здания/Животноводческие фермы|Животноводческие фермы]], [[ef/Здания/Санкт-Петербургская биржа|Санкт-Петербургская биржа]]
- **potential**: скрипт, строки 2548–2550
- **attainable**: скрипт, строки 2552–2558
- **possible**: скрипт, строки 2560–2568
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-loyalists-from-legitimacy-mult|country_loyalists_from_legitimacy_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-cash-reserves-mult|building_cash_reserves_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.075`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.075`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
