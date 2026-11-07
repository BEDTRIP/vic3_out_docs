---
type: concept
description: "Вид компании «De Beers Consolidated Mines Ltd» — ваниль 1.13, `company_de_beers`"
project: vic3
audience: agent
source: vanilla
aliases: ["De Beers Consolidated Mines Ltd", "company_de_beers"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_de_beers
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# De Beers Consolidated Mines Ltd

Вид компании · `company_de_beers` · `common/company_types/00_companies_mp1.txt:1320`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_de_beers.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CAPE_COLONY`
- **building_types**: [[vanilla/Здания/Золотые рудники|Золотые рудники]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **potential**: скрипт, строки 1336–1339
- **attainable**: пусто
- **possible**: скрипт, строки 1344–1352
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-colony-growth-speed-mult|state_colony_growth_speed_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 1360–1365
- **ai_construction_targets**: скрипт, строки 1367–1374
- **ai_weight**: скрипт, строки 1376–1378
