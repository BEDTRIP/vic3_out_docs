---
type: concept
description: "Вид компании «Banco Central de Guatemala» — E&F 1.13, `company_BancoCentralDeGuatemala`"
project: vic3
source: ef
aliases: ["Banco Central de Guatemala", "company_BancoCentralDeGuatemala"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BancoCentralDeGuatemala
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Central de Guatemala

Вид компании · `company_BancoCentralDeGuatemala` · `common/company_types/00_ef_companies.txt:5382`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banco_central_de_guatemala.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_GUATEMALA`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Financial Centre|Financial Centre]]
- **potential**: скрипт, строки 5401–5403
- **possible**: скрипт, строки 5405–5413
- **attainable**: скрипт, строки 5415–5421
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
- **ai_will_do**: скрипт, строки 5442–5444
