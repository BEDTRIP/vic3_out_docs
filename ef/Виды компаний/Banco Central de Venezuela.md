---
type: concept
description: "Вид компании «Banco Central de Venezuela» — E&F 1.13, `company_BancoCentralDeVenezuela`"
project: vic3
source: ef
aliases: ["Banco Central de Venezuela", "company_BancoCentralDeVenezuela"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BancoCentralDeVenezuela
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Central de Venezuela

Вид компании · `company_BancoCentralDeVenezuela` · `common/company_types/00_ef_companies.txt:6293`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banco_central_de_venezuela.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MIRANDA`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Financial Centre|Financial Centre]]
- **potential**: скрипт, строки 6312–6314
- **possible**: скрипт, строки 6316–6324
- **attainable**: скрипт, строки 6326–6332
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
- **ai_will_do**: скрипт, строки 6353–6355
