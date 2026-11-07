---
type: concept
description: "Вид компании «Da-Qing Bank» — E&F 1.13, `company_DaQingBank`"
project: vic3
source: ef
aliases: ["Da-Qing Bank", "company_DaQingBank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_DaQingBank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Da-Qing Bank

Вид компании · `company_DaQingBank` · `common/company_types/00_ef_companies.txt:4178`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Da_QingBank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Da_Qing_Bank`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Shanghai Sharebrokers' Association|Shanghai Sharebrokers' Association]]
- **potential**: скрипт, строки 4196–4198
- **attainable**: скрипт, строки 4200–4206
- **possible**: скрипт, строки 4208–4216
- **prosperity_modifier**:
  - `country_trade_route_competitiveness_mult` = `0.1`
  - `country_loan_interest_rate_mult` = `-0.025`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.02`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.02`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.075`
  - `country_government_dividends_reinvestment_add` = `0.075`
  - `country_government_dividends_efficiency_add` = `0.075`
  - `country_max_companies_add` = `1`
