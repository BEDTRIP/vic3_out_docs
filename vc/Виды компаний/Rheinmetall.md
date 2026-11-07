---
type: concept
description: "Вид компании «Rheinmetall» — VC 1.13, `company_rheinmetall`"
project: vic3
audience: agent
source: vc
aliases: ["Rheinmetall", "company_rheinmetall"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rheinmetall
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Rheinmetall]]"
---
# Rheinmetall

Вид компании · `company_rheinmetall` · `common/company_types/joi_companies.txt:312`

## Отличия от ваниль

- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_construction_targets**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_rheinmetall.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RUHR`, `STATE_NORTH_RHINE`
- **building_types**: [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vc/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_mm_mauser`
- **potential**: скрипт, строки 336–338
- **attainable**: скрипт, строки 340–349
- **possible**: скрипт, строки 351–368
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-combat-unit-type-siege-artillery-offense-mult|unit_combat_unit_type_siege_artillery_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-combat-unit-type-shrapnel-artillery-offense-mult|unit_combat_unit_type_shrapnel_artillery_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-steel-mult|goods_output_steel_mult]] = `0.05` → [[vanilla/Товары/Сталь|Сталь]]
- **ai_will_do**: скрипт, строки 376–385
- **ai_construction_targets**: скрипт, строки 387–418
- **ai_weight**: скрипт, строки 420–422
