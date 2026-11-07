---
type: concept
description: "Вид компании «Banco Hispano Colonial» — E&F 1.13, `company_BancoHispanoColonial`"
project: vic3
source: ef
aliases: ["Banco Hispano Colonial", "company_BancoHispanoColonial"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_BancoHispanoColonial
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Banco Hispano Colonial

Вид компании · `company_BancoHispanoColonial` · `common/company_types/00_ef_companies.txt:1267`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/banco_hispano_colonial.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Железные дороги|Железные дороги]], [[ef/Здания/Торговые центры|Торговые центры]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Bolsa de Madrid|Bolsa de Madrid]]
- **potential**: скрипт, строки 1284–1286
- **attainable**: скрипт, строки 1288–1294
- **possible**: скрипт, строки 1296–1304
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
