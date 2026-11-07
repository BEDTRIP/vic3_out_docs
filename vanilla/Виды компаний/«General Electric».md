---
type: concept
description: "Вид компании ««General Electric»» — ваниль 1.13, `company_general_electric`"
project: vic3
source: vanilla
aliases: ["«General Electric»", "General Electric", "company_general_electric"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_general_electric
paths: [.vanillaVIC3/common/company_types/00_companies_usa.txt]
---
# «General Electric»

Вид компании · `company_general_electric` · `common/company_types/00_companies_usa.txt:249`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_general_electric.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MASSACHUSETTS`, `STATE_NEW_YORK`
- **building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_radiola_radios`
- **potential**: скрипт, строки 270–272
- **attainable**: скрипт, строки 274–283
- **possible**: скрипт, строки 285–298
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Моторные заводы|Моторные заводы]]
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 305–314
- **ai_construction_targets**: скрипт, строки 316–327
- **ai_weight**: скрипт, строки 329–331
