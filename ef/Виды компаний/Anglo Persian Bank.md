---
type: concept
description: "Вид компании «Anglo Persian Bank» — E&F 1.13, `company_BankAngloPersian`"
project: vic3
source: ef
aliases: ["Anglo Persian Bank", "company_BankAngloPersian"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankAngloPersian
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Anglo Persian Bank

Вид компании · `company_BankAngloPersian` · `common/company_types/00_ef_companies.txt:3794`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/anglo_persian_bank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_IRAKAJEMI`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Financial Centre|Financial Centre]]
- **potential**: скрипт, строки 3813–3815
- **possible**: скрипт, строки 3817–3825
- **attainable**: скрипт, строки 3827–3833
- **prosperity_modifier**:
  - `building_cash_reserves_mult` = `0.05`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.075`
  - `country_government_dividends_efficiency_add` = `0.075`
  - `country_max_companies_add` = `1`
- **ai_will_do**: скрипт, строки 3854–3856
