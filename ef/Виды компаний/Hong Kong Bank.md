---
type: concept
description: "Вид компании «Hong Kong Bank» — E&F 1.13, `company_BankHSBC`"
project: vic3
source: ef
aliases: ["Hong Kong Bank", "company_BankHSBC"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankHSBC
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Hong Kong Bank

Вид компании · `company_BankHSBC` · `common/company_types/00_ef_companies.txt:3987`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Bank_HSBC.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Bank_HSBC`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Hong Kong Stock Exchange|Hong Kong Stock Exchange]]
- **potential**: скрипт, строки 4005–4017
- **attainable**: скрипт, строки 4019–4025
- **possible**: скрипт, строки 4027–4035
- **prosperity_modifier**:
  - `country_trade_route_competitiveness_mult` = `0.075`
  - `country_trade_route_cost_mult` = `-0.075`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.02`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.02`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
