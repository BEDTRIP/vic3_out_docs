---
type: concept
description: "Вид компании «Bank of England» — E&F 1.13, `company_BankofEngland`"
project: vic3
audience: agent
source: ef
aliases: ["Bank of England", "company_BankofEngland"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankofEngland
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Bank of England

Вид компании · `company_BankofEngland` · `common/company_types/00_ef_companies.txt:1783`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Bank_of_England.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Bank_of_England`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/London Stock Exchange|London Stock Exchange]], [[ef/Здания/Manchester Stock Exchange|Manchester Stock Exchange]]
- **possible_prestige_goods**: `manufacture_stock_gbr`
- **potential**: скрипт, строки 1808–1810
- **attainable**: скрипт, строки 1812–1818
- **possible**: скрипт, строки 1820–1828
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.05` → [[ef/Здания/верфи|верфи]]
  - `building_military_shipyard_throughput_add` = `0.05` → [[ef/Здания/Военные верфи|Военные верфи]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-approval-add|interest_group_ig_landowners_approval_add]] = `2`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.045`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
- **ai_weight**: скрипт, строки 1850–1852
