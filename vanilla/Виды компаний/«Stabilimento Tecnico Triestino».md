---
type: concept
description: "Вид компании ««Stabilimento Tecnico Triestino»» — ваниль 1.13, `company_stt`"
project: vic3
source: vanilla
aliases: ["«Stabilimento Tecnico Triestino»", "Stabilimento Tecnico Triestino", "company_stt"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_stt
paths: [.vanillaVIC3/common/company_types/00_companies_italy.txt]
---
# «Stabilimento Tecnico Triestino»

Вид компании · `company_stt` · `common/company_types/00_companies_italy.txt:328`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/stt.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ISTRIA`
- **building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 346–348
- **attainable**: скрипт, строки 350–356
- **possible**: скрипт, строки 358–368
- **prosperity_modifier**:
  - `ship_armor_mult` = `0.025`
  - `country_ship_group_supply_ships_construction_efficiency_add` = `0.15`
- **ai_will_do**: скрипт, строки 375–381
- **ai_construction_targets**: скрипт, строки 383–390
- **ai_weight**: скрипт, строки 392–394
