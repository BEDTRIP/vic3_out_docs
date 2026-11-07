---
type: concept
description: "Вид компании «J.P. Morgan» — E&F 1.13, `company_BankJPMorgan`"
project: vic3
source: ef
aliases: ["J.P. Morgan", "company_BankJPMorgan"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankJPMorgan
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# J.P. Morgan

Вид компании · `company_BankJPMorgan` · `common/company_types/00_ef_companies.txt:149`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Bank_JP_Morgan.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Bank_JP_Morgan`
- **preferred_headquarters**: `STATE_NEW_YORK`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/New York Stock Exchange|New York Stock Exchange]], [[ef/Здания/Chicago Stock Exchange|Chicago Stock Exchange]]
- **possible_prestige_goods**: `manufacture_stock_usa`
- **potential**: скрипт, строки 176–178
- **attainable**: скрипт, строки 180–186
- **possible**: скрипт, строки 188–196
- **prosperity_modifier**:
  - `country_minting_mult` = `0.075`
  - `building_group_bg_heavy_industry_throughput_add` = `0.05`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.01`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.01`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
