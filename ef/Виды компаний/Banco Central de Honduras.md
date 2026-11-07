---
type: concept
description: "Вид компании «Banco Central de Honduras» — E&F 1.13, `company_BancoCentralDeHonduras`"
project: vic3
source: ef
aliases: ["Banco Central de Honduras", "company_BancoCentralDeHonduras"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BancoCentralDeHonduras
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Central de Honduras

Вид компании · `company_BancoCentralDeHonduras` · `common/company_types/00_ef_companies.txt:5447`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banco_central_de_honduras.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HONDURAS`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Financial Centre|Financial Centre]]
- **potential**: скрипт, строки 5466–5468
- **possible**: скрипт, строки 5470–5478
- **attainable**: скрипт, строки 5480–5486
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
- **ai_will_do**: скрипт, строки 5507–5509
