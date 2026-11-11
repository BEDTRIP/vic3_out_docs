---
type: concept
description: "Вид компании ««A.P. Møller»» — ваниль 1.15, `company_ap_moller`"
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

Вид компании · `company_ap_moller` · `common/company_types/00_companies_europe.txt:1684`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ap_moller.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZEALAND`
- **building_types**: [[vanilla/Здания/Верфи|Верфи]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 1705–1710
- **potential**: скрипт, строки 1712–1714
- **attainable**: скрипт, строки 1716–1722
- **possible**: скрипт, строки 1724–1731
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.2`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pop-attraction-mult|interest_group_ig_industrialists_pop_attraction_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 1738–1743
- **ai_construction_targets**: скрипт, строки 1745–1752
- **ai_weight**: скрипт, строки 1754–1756
