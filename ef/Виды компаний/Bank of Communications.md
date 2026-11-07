---
type: concept
description: "Вид компании «Bank of Communications» — E&F 1.13, `company_BankBOCOM`"
project: vic3
source: ef
aliases: ["Bank of Communications", "company_BankBOCOM"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankBOCOM
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Bank of Communications

Вид компании · `company_BankBOCOM` · `common/company_types/00_ef_companies.txt:4118`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/BankCommunications.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Shanghai Sharebrokers' Association|Shanghai Sharebrokers' Association]]
- **replaces_company**: `company_Bank_BOCOM`
- **potential**: скрипт, строки 4136–4138
- **attainable**: скрипт, строки 4140–4146
- **possible**: скрипт, строки 4148–4156
- **prosperity_modifier**:
  - `building_railway_throughput_add` = `0.075` → [[ef/Здания/Железные дороги|Железные дороги]]
  - `building_urban_center_throughput_add` = `0.075` → [[vanilla/Здания/Городские центры|Городские центры]]
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.05`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
