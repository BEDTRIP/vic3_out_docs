---
type: concept
description: "Вид компании «Chase Bank» — E&F 1.13, `company_ChaseBank`"
project: vic3
source: ef
aliases: ["Chase Bank", "company_ChaseBank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ChaseBank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Chase Bank

Вид компании · `company_ChaseBank` · `common/company_types/00_ef_companies.txt:283`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Chase.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Chase_Bank`
- **preferred_headquarters**: `STATE_NEW_YORK`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/New York Stock Exchange|New York Stock Exchange]], [[ef/Здания/Chicago Stock Exchange|Chicago Stock Exchange]]
- **potential**: скрипт, строки 306–308
- **attainable**: скрипт, строки 310–316
- **possible**: скрипт, строки 318–326
- **prosperity_modifier**:
  - `interest_group_ig_industrialists_pop_attraction_mult` = `0.1`
  - `building_cash_reserves_mult` = `0.05`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.07`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
