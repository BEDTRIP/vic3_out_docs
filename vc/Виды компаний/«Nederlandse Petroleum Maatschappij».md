---
type: concept
description: "Вид компании ««Nederlandse Petroleum Maatschappij»» — VC 1.13, `company_nederlandse_petroleum`"
project: vic3
audience: agent
source: vc
aliases: ["«Nederlandse Petroleum Maatschappij»", "Nederlandse Petroleum Maatschappij", "company_nederlandse_petroleum"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nederlandse_petroleum
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Nederlandse Petroleum Maatschappij»]]"
---
# «Nederlandse Petroleum Maatschappij»

Вид компании · `company_nederlandse_petroleum` · `common/company_types/joi_companies.txt:5215`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/maatschappij.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Буровые вышки|Буровые вышки]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **potential**: скрипт, строки 5229–5231
- **possible**: скрипт, строки 5233–5243
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-colony-growth-creation-factor|state_colony_growth_creation_factor]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-employee-mult|building_group_bg_oil_extraction_employee_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.2`
- **ai_will_do**: скрипт, строки 5251–5258
- **ai_construction_targets**: скрипт, строки 5260–5268
- **ai_weight**: скрипт, строки 5270–5272
