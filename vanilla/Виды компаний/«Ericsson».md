---
type: concept
description: "Вид компании ««Ericsson»» — ваниль 1.15, `company_ericsson`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Ericsson»", "Ericsson", "company_ericsson"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ericsson
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Ericsson»

Вид компании · `company_ericsson` · `common/company_types/00_companies_europe.txt:561`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ericsson.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Медные рудники|Медные рудники]]
- **possible_prestige_goods**: `prestige_good_ericsson_apparatus`
- **potential**: скрипт, строки 582–584
- **attainable**: скрипт, строки 586–592
- **possible**: скрипт, строки 594–602
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
- **ai_will_do**: скрипт, строки 609–615
- **ai_construction_targets**: скрипт, строки 617–624
- **ai_weight**: скрипт, строки 626–628
