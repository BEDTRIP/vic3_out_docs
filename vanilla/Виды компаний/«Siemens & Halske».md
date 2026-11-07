---
type: concept
description: "Вид компании ««Siemens & Halske»» — ваниль 1.13, `company_siemens_and_halske`"
project: vic3
source: vanilla
aliases: ["«Siemens & Halske»", "Siemens & Halske", "company_siemens_and_halske"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_siemens_and_halske
paths: [.vanillaVIC3/common/company_types/00_companies_germany.txt]
---
# «Siemens & Halske»

Вид компании · `company_siemens_and_halske` · `common/company_types/00_companies_germany.txt:295`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_siemens_halske.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRANDENBURG`
- **building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **potential**: скрипт, строки 312–314
- **attainable**: скрипт, строки 316–322
- **possible**: скрипт, строки 324–334
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.15` → [[vanilla/Здания/Электростанции|Электростанции]]
- **ai_will_do**: скрипт, строки 340–346
- **ai_construction_targets**: скрипт, строки 348–355
- **ai_weight**: скрипт, строки 357–359
