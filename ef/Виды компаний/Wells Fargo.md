---
type: concept
description: "Вид компании «Wells Fargo» — E&F 1.13, `company_BankWellsFargo`"
project: vic3
source: ef
aliases: ["Wells Fargo", "company_BankWellsFargo"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankWellsFargo
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Wells Fargo

Вид компании · `company_BankWellsFargo` · `common/company_types/00_ef_companies.txt:348`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/WellsFargoBank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Bank_Wells_Fargo`
- **preferred_headquarters**: `STATE_NEW_YORK`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/New York Stock Exchange|New York Stock Exchange]], [[ef/Здания/Chicago Stock Exchange|Chicago Stock Exchange]]
- **potential**: скрипт, строки 371–373
- **attainable**: скрипт, строки 375–384
- **possible**: скрипт, строки 386–394
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-cash-reserves-mult|building_cash_reserves_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.05` → [[vanilla/Здания/Городские центры|Городские центры]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.05` → [[ef/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.02`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
