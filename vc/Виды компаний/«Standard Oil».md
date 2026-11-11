---
type: concept
description: "Вид компании ««Standard Oil»» — VC 1.15, `company_standard_oil`"
project: vic3
audience: agent
source: vc
aliases: ["«Standard Oil»", "Standard Oil", "company_standard_oil"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_standard_oil
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Standard Oil»]]"
---
# «Standard Oil»

Вид компании · `company_standard_oil` · `common/company_types/joi_companies.txt:2468`

## Отличия от ваниль

- **possible_prestige_goods**: добавлено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_standard_oil.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Буровые вышки|Буровые вышки]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]]
- **possible_prestige_goods**: `prestige_good_us_stranderd_oil`
- **potential**: скрипт, строки 2487–2489
- **attainable**: скрипт, строки 2491–2497
- **possible**: скрипт, строки 2499–2509
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.15` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-employee-mult|building_group_bg_oil_extraction_employee_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.15`
- **ai_will_do**: скрипт, строки 2517–2524
- **ai_construction_targets**: скрипт, строки 2526–2534
- **ai_weight**: скрипт, строки 2536–2538
