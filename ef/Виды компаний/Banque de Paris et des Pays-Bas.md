---
type: concept
description: "Вид компании «Banque de Paris et des Pays-Bas» — E&F 1.13, `company_BanqueDeParisEtDesPaysBas`"
project: vic3
source: ef
aliases: ["Banque de Paris et des Pays-Bas", "company_BanqueDeParisEtDesPaysBas"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BanqueDeParisEtDesPaysBas
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banque de Paris et des Pays-Bas

Вид компании · `company_BanqueDeParisEtDesPaysBas` · `common/company_types/00_ef_companies.txt:2381`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banque_de_paris_et_des_pays_bas.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bourse de Paris|Bourse de Paris]]
- **potential**: скрипт, строки 2400–2402
- **possible**: скрипт, строки 2404–2412
- **attainable**: скрипт, строки 2414–2420
- **prosperity_modifier**:
  - `building_cash_reserves_mult` = `0.05`
  - `country_loan_interest_rate_mult` = `-0.05`
  - `country_private_construction_allocation_mult` = `0.05`
  - `state_farmers_investment_pool_contribution_add` = `0.015`
  - `state_shopkeepers_investment_pool_contribution_add` = `0.015`
  - `state_clergymen_investment_pool_contribution_add` = `0.04`
  - `state_aristocrats_investment_pool_contribution_add` = `0.04`
  - `state_capitalists_investment_pool_contribution_add` = `0.065`
  - `building_nationalization_investment_return_add` = `0.05`
  - `country_government_dividends_reinvestment_add` = `0.075`
  - `country_government_dividends_efficiency_add` = `0.075`
  - `country_max_companies_add` = `1`
- **ai_will_do**: скрипт, строки 2441–2443
