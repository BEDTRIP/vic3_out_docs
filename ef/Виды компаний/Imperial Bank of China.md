---
type: concept
description: "Вид компании «Imperial Bank of China» — E&F 1.13, `company_BankIBC`"
project: vic3
source: ef
aliases: ["Imperial Bank of China", "company_BankIBC"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankIBC
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Imperial Bank of China

Вид компании · `company_BankIBC` · `common/company_types/00_ef_companies.txt:4057`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Imperial_Bank_of_China.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Bank_IBC`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Shanghai Sharebrokers' Association|Shanghai Sharebrokers' Association]]
- **potential**: скрипт, строки 4075–4077
- **attainable**: скрипт, строки 4079–4085
- **possible**: скрипт, строки 4087–4095
- **prosperity_modifier**:
  - `state_education_access_wealth_add` = `0.003`
  - `state_pop_qualifications_mult` = `0.05`
  - `country_minting_mult` = `0.025`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.03`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.04`
  - `state_clergymen_investment_pool_contribution_add` = `0.025`
  - `state_aristocrats_investment_pool_contribution_add` = `0.025`
  - `state_capitalists_investment_pool_contribution_add` = `0.075`
  - `building_nationalization_investment_return_add` = `0.025`
  - `country_government_dividends_reinvestment_add` = `0.025`
  - `country_government_dividends_efficiency_add` = `0.025`
  - `country_max_companies_add` = `1`
