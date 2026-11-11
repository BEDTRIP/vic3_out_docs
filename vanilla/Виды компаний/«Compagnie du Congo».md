---
type: concept
description: "Вид компании ««Compagnie du Congo»» — ваниль 1.15, `company_ccci`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Compagnie du Congo»", "Compagnie du Congo", "company_ccci"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ccci
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Compagnie du Congo»

Вид компании · `company_ccci` · `common/company_types/00_companies_europe.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ccci.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **potential**: скрипт, строки 21–23
- **possible**: скрипт, строки 25–44
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-rubber-mortality-mult|building_group_bg_rubber_mortality_mult]] = `0.2`
- **ai_will_do**: скрипт, строки 51–62
- **ai_construction_targets**: скрипт, строки 64–71
- **ai_weight**: скрипт, строки 73–75
