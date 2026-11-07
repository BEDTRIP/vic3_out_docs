---
type: concept
description: "Вид компании «Société générale de Belgique» — E&F 1.13, `company_SocieteGeneraledeBelgique`"
project: vic3
audience: agent
source: ef
aliases: ["Société générale de Belgique", "company_SocieteGeneraledeBelgique"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_SocieteGeneraledeBelgique
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Société générale de Belgique

Вид компании · `company_SocieteGeneraledeBelgique` · `common/company_types/00_ef_companies.txt:743`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/SGDB.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **replaces_company**: `company_SgdB`
- **preferred_headquarters**: `STATE_FLANDERS`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bourse de Bruxelles|Bourse de Bruxelles]]
- **potential**: скрипт, строки 765–770
- **attainable**: скрипт, строки 772–778
- **possible**: скрипт, строки 780–788
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-iron-mine-throughput-add|building_iron_mine_throughput_add]] = `0.05` → [[ef/Здания/Железные рудники|Железные рудники]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.05` → [[ef/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы B#^m-building-chemical-plant-throughput-add|building_chemical_plant_throughput_add]] = `0.05` → [[ef/Здания/Заводы удобрений|Заводы удобрений]]
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-contribution-add|state_farmers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-shopkeepers-investment-pool-contribution-add|state_shopkeepers_investment_pool_contribution_add]] = `0.015`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-contribution-add|state_clergymen_investment_pool_contribution_add]] = `0.04`
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-contribution-add|state_aristocrats_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-contribution-add|state_capitalists_investment_pool_contribution_add]] = `0.065`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-max-companies-add|country_max_companies_add]] = `1`
- **ai_weight**: скрипт, строки 810–812
