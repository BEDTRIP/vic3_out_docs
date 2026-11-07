---
type: concept
description: "Вид компании «Bayerische Hypotheken- und Wechsel-Bank» — E&F 1.13, `company_BayerischeHypothekenUndWechselBank`"
project: vic3
source: ef
aliases: ["Bayerische Hypotheken- und Wechsel-Bank", "company_BayerischeHypothekenUndWechselBank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BayerischeHypothekenUndWechselBank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Bayerische Hypotheken- und Wechsel-Bank

Вид компании · `company_BayerischeHypothekenUndWechselBank` · `common/company_types/00_ef_companies.txt:3005`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/bayerische_hypo_bank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAVARIA`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Münchener Börse|Münchener Börse]]
- **potential**: скрипт, строки 3024–3026
- **possible**: скрипт, строки 3028–3036
- **attainable**: скрипт, строки 3038–3044
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
- **ai_will_do**: скрипт, строки 3065–3067
