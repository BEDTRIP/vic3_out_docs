---
type: concept
description: "Вид компании ««Estaleiro Mauá»» — ваниль 1.13, `company_estaleiro_maua`"
project: vic3
source: vanilla
aliases: ["«Estaleiro Mauá»", "Estaleiro Mauá", "company_estaleiro_maua"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_estaleiro_maua
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Estaleiro Mauá»

Вид компании · `company_estaleiro_maua` · `common/company_types/00_companies_cots.txt:89`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_estaleiro_maua.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RIO_DE_JANEIRO`
- **building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **potential**: скрипт, строки 106–109
- **attainable**: скрипт, строки 111–117
- **possible**: скрипт, строки 119–131
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 138–143
- **ai_construction_targets**: скрипт, строки 145–158
- **ai_weight**: скрипт, строки 160–162
