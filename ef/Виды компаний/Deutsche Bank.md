---
type: concept
description: "Вид компании «Deutsche Bank» — E&F 1.13, `company_DeutscheBank`"
project: vic3
source: ef
aliases: ["Deutsche Bank", "company_DeutscheBank"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_DeutscheBank
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Deutsche Bank

Вид компании · `company_DeutscheBank` · `common/company_types/00_ef_companies.txt:2739`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/DeutscheBank.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_Deutsche_Bank`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Börse zu Berlin|Börse zu Berlin]]
- **potential**: скрипт, строки 2757–2762
- **possible**: скрипт, строки 2764–2772
- **prosperity_modifier**:
  - `country_authority_mult` = `0.1`
  - `building_electrics_industry_throughput_add` = `0.05` → [[ef/Здания/Электрозаводы|Электрозаводы]]
  - `country_company_throughput_bonus_add` = `0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.02`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.07`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.05`
  - `country_government_dividends_efficiency_add` = `0.05`
  - `country_max_companies_add` = `1`
