---
type: concept
description: "Вид компании ««F. Schichau»» — ваниль 1.13, `company_schichau`"
project: vic3
source: vanilla
aliases: ["«F. Schichau»", "F. Schichau", "company_schichau"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_schichau
paths: [.vanillaVIC3/common/company_types/00_companies_germany.txt]
---
# «F. Schichau»

Вид компании · `company_schichau` · `common/company_types/00_companies_germany.txt:212`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_schichau.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WEST_PRUSSIA`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/верфи|верфи]]
- **possible_prestige_goods**: `prestige_good_schichau_engines`
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 234–236
- **attainable**: скрипт, строки 238–244
- **possible**: скрипт, строки 246–259
- **prosperity_modifier**:
  - `ship_hull_damage_mult` = `0.025`
  - `ship_ship_type_submarine_hull_damage_mult` = `0.05`
- **ai_will_do**: скрипт, строки 266–272
- **ai_construction_targets**: скрипт, строки 274–287
- **ai_weight**: скрипт, строки 289–291
