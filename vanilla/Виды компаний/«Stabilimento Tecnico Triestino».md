---
type: explanation
description: "Вид компании ««Stabilimento Tecnico Triestino»» — ваниль 1.15.2, `company_stt`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Stabilimento Tecnico Triestino»", "Stabilimento Tecnico Triestino", "company_stt"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_stt
paths: [.vanillaVIC3/common/company_types/00_companies_italy.txt]
---
# «Stabilimento Tecnico Triestino»

Вид компании · `company_stt` · `common/company_types/00_companies_italy.txt:332`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/stt.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ISTRIA`
- **building_types**: [[vanilla/Здания/Верфи|Верфи]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 350–352
- **attainable**: скрипт, строки 354–360
- **possible**: скрипт, строки 362–374
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-armor-mult|ship_armor_mult]] = `0.025`
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.15`
- **ai_will_do**: скрипт, строки 381–387
- **ai_construction_targets**: скрипт, строки 389–396
- **ai_weight**: скрипт, строки 398–400
