---
type: concept
description: "Вид компании «N M Rothschild & Sons» — E&F 1.13, `company_Rothschild_Bank_gbr`"
project: vic3
source: ef
aliases: ["N M Rothschild & Sons", "company_Rothschild_Bank_gbr"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Rothschild_Bank_gbr
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# N M Rothschild & Sons

Вид компании · `company_Rothschild_Bank_gbr` · `common/company_types/00_ef_companies.txt:2126`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/company_Rothschild_Bank_gbr.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **replaces_company**: `company_Rothschild_Bank_Europe`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/London Stock Exchange|London Stock Exchange]], [[ef/Здания/Manchester Stock Exchange|Manchester Stock Exchange]]
- **possible_prestige_goods**: `manufacture_stock_gbr_2`
- **potential**: скрипт, строки 2148–2150
- **possible**: скрипт, строки 2152–2160
- **attainable**: скрипт, строки 2162–2168
- **prosperity_modifier**:
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
- **ai_will_do**: скрипт, строки 2189–2191
