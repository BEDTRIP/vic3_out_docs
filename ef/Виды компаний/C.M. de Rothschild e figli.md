---
type: concept
description: "Вид компании «C.M. de Rothschild e figli» — E&F 1.13, `company_Rothschild_Bank_ita`"
project: vic3
source: ef
aliases: ["C.M. de Rothschild e figli", "company_Rothschild_Bank_ita"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Rothschild_Bank_ita
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# C.M. de Rothschild e figli

Вид компании · `company_Rothschild_Bank_ita` · `common/company_types/00_ef_companies.txt:1522`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/company_Rothschild_Bank_ita.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **preferred_headquarters**: `STATE_CAMPANIA`
- **flavored_company**: `yes`
- **replaces_company**: `company_Rothschild_Bank_Europe`
- **building_types**: [[ef/Здания/Borsa Italiana|Borsa Italiana]], [[ef/Здания/Borsa di Toscana|Borsa di Toscana]], [[ef/Здания/Borsa di Napoli|Borsa di Napoli]], [[ef/Здания/Borsa di Cagliari|Borsa di Cagliari]]
- **potential**: скрипт, строки 1537–1539
- **attainable**: скрипт, строки 1541–1547
- **possible**: скрипт, строки 1549–1557
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
- **ai_weight**: скрипт, строки 1579–1581
