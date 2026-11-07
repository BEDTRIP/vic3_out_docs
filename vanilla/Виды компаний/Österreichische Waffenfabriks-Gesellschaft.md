---
type: concept
description: "Вид компании «Österreichische Waffenfabriks-Gesellschaft» — ваниль 1.13, `company_oevg`"
project: vic3
audience: agent
source: vanilla
aliases: ["Österreichische Waffenfabriks-Gesellschaft", "company_oevg"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_oevg
paths: [.vanillaVIC3/common/company_types/00_companies_austria_hungary.txt]
---
# Österreichische Waffenfabriks-Gesellschaft

Вид компании · `company_oevg` · `common/company_types/00_companies_austria_hungary.txt:343`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/oevg.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_generic_small_arms`
- **prestige_goods_trigger**: скрипт, строки 366–371
- **potential**: скрипт, строки 373–375
- **attainable**: скрипт, строки 377–383
- **possible**: скрипт, строки 385–395
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-munition-plant-throughput-add|building_munition_plant_throughput_add]] = `0.1` → [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 402–408
- **ai_construction_targets**: скрипт, строки 410–417
- **ai_weight**: скрипт, строки 419–421
