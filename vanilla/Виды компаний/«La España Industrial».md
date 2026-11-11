---
type: concept
description: "Вид компании ««La España Industrial»» — ваниль 1.15, `company_espana_industrial`"
project: vic3
audience: agent
source: vanilla
aliases: ["«La España Industrial»", "La España Industrial", "company_espana_industrial"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_espana_industrial
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «La España Industrial»

Вид компании · `company_espana_industrial` · `common/company_types/00_companies_europe.txt:1363`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/spain_la_espana_industrial.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CATALONIA`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **extension_building_types**: [[vanilla/Здания/Плантации шёлка|Плантации шёлка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 1384–1389
- **potential**: скрипт, строки 1391–1393
- **attainable**: скрипт, строки 1395–1401
- **possible**: скрипт, строки 1403–1411
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.15`
- **ai_will_do**: скрипт, строки 1417–1423
- **ai_construction_targets**: скрипт, строки 1425–1432
- **ai_weight**: скрипт, строки 1434–1436
