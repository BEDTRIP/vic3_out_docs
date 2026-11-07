---
type: concept
description: "Вид компании «Standard Bank of British South Africa» — E&F 1.13, `company_BankSBoBSA`"
project: vic3
source: ef
aliases: ["Standard Bank of British South Africa", "company_BankSBoBSA"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BankSBoBSA
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Standard Bank of British South Africa

Вид компании · `company_BankSBoBSA` · `common/company_types/00_ef_companies.txt:6557`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/BankOfSouthAfrica.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Bank_SBoBSA`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Johannesburg Stock Exchange|Johannesburg Stock Exchange]]
- **potential**: скрипт, строки 6575–6577
- **attainable**: скрипт, строки 6579–6588
- **possible**: скрипт, строки 6590–6598
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-gold-mine-throughput-add|building_gold_mine_throughput_add]] = `0.15` → [[ef/Здания/Золотые рудники|Золотые рудники]]
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
