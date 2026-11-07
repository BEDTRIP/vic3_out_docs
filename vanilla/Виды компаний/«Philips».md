---
type: concept
description: "Вид компании ««Philips»» — ваниль 1.13, `company_philips`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Philips»", "Philips", "company_philips"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_philips
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Philips»

Вид компании · `company_philips` · `common/company_types/00_companies_europe.txt:308`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/philips.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`, `STATE_GELRE`
- **building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_philips_chapel_radio`
- **potential**: скрипт, строки 329–331
- **attainable**: скрипт, строки 333–342
- **possible**: скрипт, строки 344–357
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `15`
- **ai_will_do**: скрипт, строки 364–373
- **ai_construction_targets**: скрипт, строки 375–386
- **ai_weight**: скрипт, строки 388–390
