---
type: concept
description: "Вид компании «Rheinmetall» — ваниль 1.15, `company_rheinmetall`"
project: vic3
audience: agent
source: vanilla
aliases: ["Rheinmetall", "company_rheinmetall"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rheinmetall
paths: [.vanillaVIC3/common/company_types/00_companies_germany.txt]
---
# Rheinmetall

Вид компании · `company_rheinmetall` · `common/company_types/00_companies_germany.txt:92`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_rheinmetall.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RUHR`, `STATE_NORTH_RHINE`
- **building_types**: [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_artillery`
- **prestige_goods_trigger**: скрипт, строки 115–120
- **potential**: скрипт, строки 122–124
- **attainable**: скрипт, строки 126–135
- **possible**: скрипт, строки 137–154
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-combat-unit-type-siege-artillery-offense-mult|unit_combat_unit_type_siege_artillery_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-combat-unit-type-shrapnel-artillery-offense-mult|unit_combat_unit_type_shrapnel_artillery_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-army-defense-mult|unit_army_defense_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 162–171
- **ai_construction_targets**: скрипт, строки 173–204
- **ai_weight**: скрипт, строки 206–208
