---
type: explanation
description: "Вид компании ««Duro y Compañía»» — ваниль 1.15.2, `company_duro_y_compania`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Duro y Compañía»", "Duro y Compañía", "company_duro_y_compania"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_duro_y_compania
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Duro y Compañía»

Вид компании · `company_duro_y_compania` · `common/company_types/00_companies_europe.txt:1304`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/spain_duro_y_compania.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ASTURIAS`
- **building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 1326–1331
- **potential**: скрипт, строки 1333–1335
- **attainable**: скрипт, строки 1337–1343
- **possible**: скрипт, строки 1345–1357
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-arms-industry-throughput-add|building_arms_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Оружейные заводы|Оружейные заводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-artillery-foundry-throughput-add|building_artillery_foundry_throughput_add]] = `0.1` → [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **ai_will_do**: скрипт, строки 1364–1370
- **ai_construction_targets**: скрипт, строки 1372–1379
- **ai_weight**: скрипт, строки 1381–1383
