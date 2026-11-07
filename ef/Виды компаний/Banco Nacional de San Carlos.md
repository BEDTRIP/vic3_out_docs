---
type: concept
description: "Вид компании «Banco Nacional de San Carlos» — E&F 1.13, `company_BankofSpain`"
project: vic3
source: ef
aliases: ["Banco Nacional de San Carlos", "company_BankofSpain"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankofSpain
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Nacional de San Carlos

Вид компании · `company_BankofSpain` · `common/company_types/00_ef_companies.txt:1150`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/BankSpain.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Bank_of_Spain`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bolsa de Madrid|Bolsa de Madrid]]
- **potential**: скрипт, строки 1168–1170
- **attainable**: скрипт, строки 1172–1178
- **possible**: скрипт, строки 1180–1188
- **prosperity_modifier**:
  - `country_diplomatic_play_maneuvers_add` = `10`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.045`
  - `state_capitalists_investment_pool_contribution_add` = `0.07`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
