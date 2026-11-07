---
type: concept
description: "Вид компании «Jusighoesa joheung-eunhaeng» — E&F 1.13, `company_ChohungBank`"
project: vic3
source: ef
aliases: ["Jusighoesa joheung-eunhaeng", "company_ChohungBank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ChohungBank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Jusighoesa joheung-eunhaeng

Вид компании · `company_ChohungBank` · `common/company_types/00_ef_companies.txt:3926`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Chohung_Bank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Chohung_Bank`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Financial Centre|Financial Centre]]
- **potential**: скрипт, строки 3945–3947
- **attainable**: скрипт, строки 3949–3955
- **possible**: скрипт, строки 3957–3965
- **prosperity_modifier**:
  - `interest_group_in_government_approval_add` = `1`
  - `interest_group_in_opposition_approval_add` = `1`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
