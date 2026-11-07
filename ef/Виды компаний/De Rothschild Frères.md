---
type: concept
description: "Вид компании «De Rothschild Frères» — E&F 1.13, `company_Rothschild_Bank_fra`"
project: vic3
source: ef
aliases: ["De Rothschild Frères", "company_Rothschild_Bank_fra"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Rothschild_Bank_fra
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# De Rothschild Frères

Вид компании · `company_Rothschild_Bank_fra` · `common/company_types/00_ef_companies.txt:2445`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/company_Rothschild_Bank_fra.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Rothschild_Bank_Europe`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **possible_prestige_goods**: `railroad_stock_fra`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bourse de Paris|Bourse de Paris]]
- **potential**: скрипт, строки 2471–2474
- **attainable**: скрипт, строки 2476–2483
- **possible**: скрипт, строки 2485–2493
- **prosperity_modifier**:
  - `country_military_goods_cost_mult` = `-0.075`
  - `country_max_weekly_construction_progress_add` = `7.5`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.07`
  - `state_capitalists_investment_pool_contribution_add` = `0.05`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
- **ai_weight**: скрипт, строки 2515–2517
