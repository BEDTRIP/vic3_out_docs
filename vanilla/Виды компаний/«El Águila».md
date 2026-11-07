---
type: concept
description: "Вид компании ««El Águila»» — ваниль 1.13, `company_el_aguila`"
project: vic3
audience: agent
source: vanilla
aliases: ["«El Águila»", "El Águila", "company_el_aguila"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_el_aguila
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «El Águila»

Вид компании · `company_el_aguila` · `common/company_types/00_companies_americas.txt:81`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/el_aguila.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Буровые вышки|Буровые вышки]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **potential**: скрипт, строки 95–97
- **attainable**: скрипт, строки 99–105
- **possible**: скрипт, строки 107–118
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.15`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-approval-add|interest_group_ig_industrialists_approval_add]] = `3`
- **ai_will_do**: скрипт, строки 125–133
- **ai_construction_targets**: скрипт, строки 135–144
- **ai_weight**: скрипт, строки 146–148
