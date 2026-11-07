---
type: concept
description: "Вид компании ««Steaua Română»» — VC 1.13, `company_romanian_star`"
project: vic3
audience: agent
source: vc
aliases: ["«Steaua Română»", "Steaua Română", "company_romanian_star"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_romanian_star
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Steaua Română»]]"
---
# «Steaua Română»

Вид компании · `company_romanian_star` · `common/company_types/joi_companies.txt:5738`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/romania_steaua_romana.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WALLACHIA`
- **building_types**: [[vc/Здания/Буровые вышки|Буровые вышки]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **potential**: скрипт, строки 5754–5756
- **attainable**: скрипт, строки 5758–5764
- **possible**: скрипт, строки 5766–5776
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.2`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-employee-mult|building_group_bg_oil_extraction_employee_mult]] = `-0.1`
- **ai_will_do**: скрипт, строки 5783–5789
- **ai_construction_targets**: скрипт, строки 5791–5798
- **ai_weight**: скрипт, строки 5800–5802
