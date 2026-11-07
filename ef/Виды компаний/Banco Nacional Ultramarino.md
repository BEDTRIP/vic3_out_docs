---
type: concept
description: "Вид компании «Banco Nacional Ultramarino» — E&F 1.13, `company_Bank_Ultramarino`"
project: vic3
audience: agent
source: ef
aliases: ["Banco Nacional Ultramarino", "company_Bank_Ultramarino"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Bank_Ultramarino
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Nacional Ultramarino

Вид компании · `company_Bank_Ultramarino` · `common/company_types/00_ef_companies.txt:1455`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/Bank_Ultramarino.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bolsa de Valores de Lisboa|Bolsa de Valores de Lisboa]]
- **potential**: скрипт, строки 1472–1478
- **attainable**:
  - **hidden_trigger**:
    - `country_has_primary_culture` = `cu:portuguese`
- **possible**: скрипт, строки 1486–1498
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-institution-colonial-affairs-max-investment-add|country_institution_colonial_affairs_max_investment_add]] = `1`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.025`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
