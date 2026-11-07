---
type: concept
description: "Вид компании ««Forges et Chantiers de la Méditerranée»» — VC 1.13, `company_fcm`"
project: vic3
audience: agent
source: vc
aliases: ["«Forges et Chantiers de la Méditerranée»", "Forges et Chantiers de la Méditerranée", "company_fcm"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fcm
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Forges et Chantiers de la Méditerranée»]]"
---
# «Forges et Chantiers de la Méditerranée»

Вид компании · `company_fcm` · `common/company_types/joi_companies.txt:4634`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: добавлено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_forges_et_chantiers_de_la_méditerranée.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PROVENCE`, `STATE_ALGIERS`
- **building_types**: [[vc/Здания/верфи|верфи]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **potential**: скрипт, строки 4655–4657
- **attainable**: скрипт, строки 4659–4665
- **possible**: скрипт, строки 4667–4677
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-armor-mult|ship_armor_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы U#^m-unit-combat-unit-type-heavy-tank-offense-mult|unit_combat_unit_type_heavy_tank_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-hull-damage-mult|ship_hull_damage_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 4685–4691
- **ai_construction_targets**: скрипт, строки 4693–4700
- **ai_weight**: скрипт, строки 4702–4704
