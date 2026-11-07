---
type: concept
description: "Вид компании ««Forges et Chantiers de la Méditerranée»» — ваниль 1.13, `company_fcm`"
project: vic3
source: vanilla
aliases: ["«Forges et Chantiers de la Méditerranée»", "Forges et Chantiers de la Méditerranée", "company_fcm"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fcm
paths: [.vanillaVIC3/common/company_types/00_companies_france.txt]
---
# «Forges et Chantiers de la Méditerranée»

Вид компании · `company_fcm` · `common/company_types/00_companies_france.txt:367`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_forges_et_chantiers_de_la_méditerranée.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PROVENCE`
- **building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 384–386
- **attainable**: скрипт, строки 388–394
- **possible**: скрипт, строки 396–406
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-hull-damage-mult|ship_hull_damage_mult]] = `0.025`
  - [[vanilla/движок/Модификаторы U#^m-unit-combat-unit-type-heavy-tank-offense-mult|unit_combat_unit_type_heavy_tank_offense_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 413–419
- **ai_construction_targets**: скрипт, строки 421–428
- **ai_weight**: скрипт, строки 430–432
