---
type: concept
description: "Вид компании «Banco de la Provincia de Buenos Aires» — E&F 1.13, `company_BancoProvincia`"
project: vic3
source: ef
aliases: ["Banco de la Provincia de Buenos Aires", "company_BancoProvincia"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BancoProvincia
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco de la Provincia de Buenos Aires

Вид компании · `company_BancoProvincia` · `common/company_types/00_ef_companies.txt:5901`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banco_provincia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BUENOS_AIRES`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bolsa de Comercio de Buenos Aires|Bolsa de Comercio de Buenos Aires]]
- **potential**: скрипт, строки 5920–5922
- **possible**: скрипт, строки 5924–5932
- **attainable**: скрипт, строки 5934–5940
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
- **ai_will_do**: скрипт, строки 5961–5963
