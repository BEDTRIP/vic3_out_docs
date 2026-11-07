---
type: concept
description: "Вид компании «Amsterdamsche Bank» — E&F 1.13, `company_amsterdamschebank`"
project: vic3
audience: agent
source: ef
aliases: ["Amsterdamsche Bank", "company_amsterdamschebank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_amsterdamschebank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Amsterdamsche Bank

Вид компании · `company_amsterdamschebank` · `common/company_types/00_ef_companies.txt:549`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/amsterdamsche_bank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_amsterdamsche_bank`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Beurs van Amsterdam|Beurs van Amsterdam]]
- **potential**: скрипт, строки 567–569
- **attainable**: скрипт, строки 571–577
- **possible**: скрипт, строки 579–587
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-base-add|country_legitimacy_base_add]] = `5`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-approval-add|interest_group_ig_landowners_approval_add]] = `2`
  - [[vanilla/движок/Модификаторы C#^m-country-minting-mult|country_minting_mult]] = `0.025`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.025`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
