---
type: concept
description: "Вид компании ««F. Schichau»» — VC 1.13, `company_schichau`"
project: vic3
audience: agent
source: vc
aliases: ["«F. Schichau»", "F. Schichau", "company_schichau"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_schichau
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«F. Schichau»]]"
---
# «F. Schichau»

Вид компании · `company_schichau` · `common/company_types/joi_companies.txt:6346`

## Отличия от ваниль

- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_construction_targets**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_schichau.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WEST_PRUSSIA`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/верфи|верфи]]
- **possible_prestige_goods**: `prestige_good_schichau_engines`
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 6368–6370
- **attainable**: скрипт, строки 6372–6378
- **possible**: скрипт, строки 6380–6390
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-ship-construction-efficiency-add|country_ship_construction_efficiency_add]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-hull-damage-mult|ship_hull_damage_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-visibility-mult|ship_visibility_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 6398–6404
- **ai_construction_targets**: скрипт, строки 6406–6413
- **ai_weight**: скрипт, строки 6415–6417
