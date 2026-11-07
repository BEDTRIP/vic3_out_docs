---
type: concept
description: "Вид компании «Első Budapesti Gőzmalom Rt» — ваниль 1.13, `company_elso_budapesti_gozmalom`"
project: vic3
audience: agent
source: vanilla
aliases: ["Első Budapesti Gőzmalom Rt", "company_elso_budapesti_gozmalom"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_elso_budapesti_gozmalom
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Első Budapesti Gőzmalom Rt

Вид компании · `company_elso_budapesti_gozmalom` · `common/company_types/00_companies_ip3.txt:381`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_elso_budapesti_gozmalom.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_pannonian_patent_flour`
- **potential**: скрипт, строки 400–403
- **attainable**: скрипт, строки 405–413
- **possible**: скрипт, строки 415–432
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-wheat-farm-throughput-add|building_wheat_farm_throughput_add]] = `0.15` → [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 439–445
- **ai_construction_targets**: скрипт, строки 447–460
- **ai_weight**: скрипт, строки 462–464
