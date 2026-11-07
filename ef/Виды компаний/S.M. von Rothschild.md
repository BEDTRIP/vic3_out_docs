---
type: concept
description: "Вид компании «S.M. von Rothschild» — E&F 1.13, `company_Rothschild_Bank_aus`"
project: vic3
source: ef
aliases: ["S.M. von Rothschild", "company_Rothschild_Bank_aus"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Rothschild_Bank_aus
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# S.M. von Rothschild

Вид компании · `company_Rothschild_Bank_aus` · `common/company_types/00_ef_companies.txt:3268`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/company_Rothschild_Bank_aus.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **preferred_headquarters**: `STATE_BOHEMIA`
- **flavored_company**: `yes`
- **replaces_company**: `company_Rothschild_Bank_Europe`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Wiener Börse|Wiener Börse]]
- **potential**: скрипт, строки 3289–3292
- **attainable**: скрипт, строки 3294–3301
- **possible**: скрипт, строки 3303–3311
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
- **ai_weight**: скрипт, строки 3333–3335
