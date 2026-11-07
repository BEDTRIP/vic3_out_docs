---
type: concept
description: "Вид компании «Bank» — E&F 1.13, `company_BasicBank`"
project: vic3
source: ef
aliases: ["Bank", "company_BasicBank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BasicBank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Bank

Вид компании · `company_BasicBank` · `common/company_types/00_ef_companies.txt:21`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/BasicBank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_basic_bank`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_consortium`, `dynamic_company_type_corporation`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Financial Centre|Financial Centre]]
- **potential**: пусто
- **possible**: скрипт, строки 100–108
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-minting-mult|country_minting_mult]] = `0.075`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-throughput-add|building_group_bg_heavy_industry_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.01`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.01`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
- **ai_will_do**: скрипт, строки 130–132
- **ai_construction_targets**: скрипт, строки 134–141
- **ai_weight**: скрипт, строки 143–145
