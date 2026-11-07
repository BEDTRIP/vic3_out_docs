---
type: concept
description: "Вид компании «Banque de Montréal» — E&F 1.13, `company_BankOfMontreal`"
project: vic3
source: ef
aliases: ["Banque de Montréal", "company_BankOfMontreal"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankOfMontreal
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banque de Montréal

Вид компании · `company_BankOfMontreal` · `common/company_types/00_ef_companies.txt:4730`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/bank_of_montreal.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Bank_of_Montreal`
- **preferred_headquarters**: `STATE_QUEBEC`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bourse de Montréal|Bourse de Montréal]]
- **potential**: скрипт, строки 4750–4752
- **possible**: скрипт, строки 4754–4762
- **attainable**: скрипт, строки 4764–4770
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
- **ai_will_do**: скрипт, строки 4791–4793
