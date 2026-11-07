---
type: concept
description: "Вид компании «S.M. von Rothschild» — E&F 1.13, `company_Rothschild_Bank_aus`"
project: vic3
source: ef
aliases: ["S.M. von Rothschild", "company_Rothschild_Bank_aus"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Rothschild_Bank_aus
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# S.M. von Rothschild

Вид компании · `company_Rothschild_Bank_aus` · `common/company_types/00_ef_companies.txt:3268`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/company_Rothschild_Bank_aus.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **preferred_headquarters**: `STATE_BOHEMIA`
- **flavored_company**: `yes`
- **replaces_company**: `company_Rothschild_Bank_Europe`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Wiener Börse|Wiener Börse]]
- **potential**: скрипт, строки 3289–3292
- **attainable**: скрипт, строки 3294–3301
- **possible**: скрипт, строки 3303–3311
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-military-goods-cost-mult|country_military_goods_cost_mult]] = `-0.075`
  - [[vanilla/движок/Модификаторы C#^m-country-max-weekly-construction-progress-add|country_max_weekly_construction_progress_add]] = `7.5`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.07`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
- **ai_weight**: скрипт, строки 3333–3335
