---
type: concept
description: "Вид компании «Bankenverein» — E&F 1.13, `company_Bankenverein`"
project: vic3
source: ef
aliases: ["Bankenverein", "company_Bankenverein"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Bankenverein
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Bankenverein

Вид компании · `company_Bankenverein` · `common/company_types/00_ef_companies.txt:883`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/UBS.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EAST_SWITZERLAND`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bourses de Genève|Bourses de Genève]]
- **potential**: скрипт, строки 904–906
- **attainable**: скрипт, строки 908–914
- **possible**: скрипт, строки 916–924
- **prosperity_modifier**:
  - `building_railway_throughput_add` = `0.1` → [[ef/Здания/Железные дороги|Железные дороги]]
  - `interest_group_ig_trade_unions_approval_add` = `2`
  - `country_loan_interest_rate_mult` = `-0.15`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.025`
  - `country_government_dividends_efficiency_add` = `0.025`
  - `country_max_companies_add` = `1`
