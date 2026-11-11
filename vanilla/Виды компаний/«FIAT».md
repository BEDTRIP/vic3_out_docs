---
type: concept
description: "Вид компании ««FIAT»» — ваниль 1.15, `company_fiat`"
project: vic3
audience: agent
source: vanilla
aliases: ["«FIAT»", "FIAT", "company_fiat"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fiat
paths: [.vanillaVIC3/common/company_types/00_companies_italy.txt]
---
# «FIAT»

Вид компании · `company_fiat` · `common/company_types/00_companies_italy.txt:241`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/fiat.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PIEDMONT`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 262–264
- **attainable**: скрипт, строки 266–272
- **possible**: скрипт, строки 274–288
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы M#^m-military-formation-army-movement-speed-mult|military_formation_army_movement_speed_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-army-offense-mult|unit_army_offense_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 295–301
- **ai_construction_targets**: скрипт, строки 303–316
- **ai_weight**: скрипт, строки 318–320
