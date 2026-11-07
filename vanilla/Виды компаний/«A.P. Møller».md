---
type: concept
description: "Вид компании ««A.P. Møller»» — ваниль 1.13, `company_ap_moller`"
project: vic3
audience: agent
source: vanilla
aliases: ["«A.P. Møller»", "A.P. Møller", "company_ap_moller"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ap_moller
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «A.P. Møller»

Вид компании · `company_ap_moller` · `common/company_types/00_companies_europe.txt:1701`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ap_moller.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZEALAND`
- **building_types**: [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 1722–1727
- **potential**: скрипт, строки 1729–1731
- **attainable**: скрипт, строки 1733–1739
- **possible**: скрипт, строки 1741–1750
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.2`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pop-attraction-mult|interest_group_ig_industrialists_pop_attraction_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 1757–1762
- **ai_construction_targets**: скрипт, строки 1764–1771
- **ai_weight**: скрипт, строки 1773–1775
