---
type: concept
description: "Вид компании «M.A. Rothschild & Söhne» — E&F 1.13, `company_Rothschild_Bank_ger`"
project: vic3
source: ef
aliases: ["M.A. Rothschild & Söhne", "company_Rothschild_Bank_ger"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Rothschild_Bank_ger
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# M.A. Rothschild & Söhne

Вид компании · `company_Rothschild_Bank_ger` · `common/company_types/00_ef_companies.txt:2931`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/company_Rothschild_Bank_ger.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_Rothschild_Bank_Europe`
- **possible_prestige_goods**: `railroad_stock_ger`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Frankfurter Wertpapierbörse|Frankfurter Wertpapierbörse]], [[ef/Здания/Börse zu Berlin|Börse zu Berlin]]
- **potential**: скрипт, строки 2956–2958
- **attainable**: скрипт, строки 2960–2967
- **possible**: скрипт, строки 2969–2977
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
- **ai_weight**: скрипт, строки 2999–3001
