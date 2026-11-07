---
type: concept
description: "Вид компании ««Tata»» — ваниль 1.13, `company_tata`"
project: vic3
source: vanilla
aliases: ["«Tata»", "Tata", "company_tata"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_tata
paths: [.vanillaVIC3/common/company_types/00_companies_asia.txt]
---
# «Tata»

Вид компании · `company_tata` · `common/company_types/00_companies_asia.txt:467`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/india_tata.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BOMBAY`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 489–494
- **potential**: скрипт, строки 496–498
- **attainable**: скрипт, строки 500–506
- **possible**: скрипт, строки 508–520
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.05` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
  - [[vanilla/движок/Модификаторы C#^m-country-max-weekly-construction-progress-add|country_max_weekly_construction_progress_add]] = `10`
- **ai_will_do**: скрипт, строки 527–532
- **ai_construction_targets**: скрипт, строки 534–547
- **ai_weight**: скрипт, строки 549–551
