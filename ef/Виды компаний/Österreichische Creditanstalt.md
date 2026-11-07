---
type: concept
description: "Вид компании «Österreichische Creditanstalt» — E&F 1.13, `company_OesterreichischeCreditAnstalt`"
project: vic3
source: ef
aliases: ["Österreichische Creditanstalt", "company_OesterreichischeCreditAnstalt"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_OesterreichischeCreditAnstalt
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Österreichische Creditanstalt

Вид компании · `company_OesterreichischeCreditAnstalt` · `common/company_types/00_ef_companies.txt:3135`

## Поля

- **icon**: `gfx/interface/icons/company_icons/bank/oesterreichische_creditanstalt.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]], [[ef/Здания/Угольные шахты|Угольные шахты]], [[ef/Здания/Железные рудники|Железные рудники]], [[ef/Здания/Свинцовые рудники|Свинцовые рудники]], [[ef/Здания/Серные рудники|Серные рудники]], [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Wiener Börse|Wiener Börse]]
- **possible_prestige_goods**: `mining_stock_aus`
- **potential**: скрипт, строки 3159–3161
- **possible**: скрипт, строки 3163–3171
- **attainable**: скрипт, строки 3173–3179
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
- **ai_will_do**: скрипт, строки 3200–3202
