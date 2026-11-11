---
type: concept
description: "Вид компании «Österreichische Waffenfabriks-Gesellschaft» — VC 1.15, `company_oevg`"
project: vic3
audience: agent
source: vc
aliases: ["Österreichische Waffenfabriks-Gesellschaft", "company_oevg"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_oevg
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Österreichische Waffenfabriks-Gesellschaft]]"
---
# Österreichische Waffenfabriks-Gesellschaft

Вид компании · `company_oevg` · `common/company_types/joi_companies.txt:8201`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **potential**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/oevg.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRANDENBURG`, `STATE_AUSTRIA`
- **building_types**: [[vc/Здания/Оружейные заводы|Оружейные заводы]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vc/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **extension_building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vc/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_generic_small_arms`
- **potential**: скрипт, строки 8225–8230
- **attainable**: скрипт, строки 8232–8238
- **possible**: скрипт, строки 8240–8250
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-explosives-mult|goods_output_explosives_mult]] = `0.15` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-small-arms-mult|goods_output_small_arms_mult]] = `0.1` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 8258–8264
- **ai_construction_targets**: скрипт, строки 8266–8273
- **ai_weight**: скрипт, строки 8275–8277
