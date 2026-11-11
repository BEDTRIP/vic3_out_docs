---
type: concept
description: "Вид компании «John Holt and Company» — ваниль 1.15, `company_john_holt`"
project: vic3
audience: agent
source: vanilla
aliases: ["John Holt and Company", "company_john_holt"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_john_holt
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# John Holt and Company

Вид компании · `company_john_holt` · `common/company_types/00_companies_mp1.txt:1369`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_john_holt.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vanilla/Здания/Верфи|Верфи]]
- **potential**: скрипт, строки 1385–1387
- **attainable**: пусто
- **possible**: скрипт, строки 1392–1401
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 1408–1413
- **ai_construction_targets**: скрипт, строки 1415–1422
- **ai_weight**: скрипт, строки 1424–1426
