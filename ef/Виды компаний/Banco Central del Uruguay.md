---
type: concept
description: "Вид компании «Banco Central del Uruguay» — E&F 1.13, `company_BancoCentralDelUruguay`"
project: vic3
source: ef
aliases: ["Banco Central del Uruguay", "company_BancoCentralDelUruguay"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BancoCentralDelUruguay
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Central del Uruguay

Вид компании · `company_BancoCentralDelUruguay` · `common/company_types/00_ef_companies.txt:6425`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banco_central_del_uruguay.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_URUGUAY`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bolsa de Valores de Montevideo|Bolsa de Valores de Montevideo]]
- **potential**: скрипт, строки 6444–6446
- **possible**: скрипт, строки 6448–6456
- **attainable**: скрипт, строки 6458–6464
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
- **ai_will_do**: скрипт, строки 6485–6487
