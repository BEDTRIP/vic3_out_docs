---
type: concept
description: "Вид компании ««FIAT»» — VC 1.15, `company_fiat`"
project: vic3
audience: agent
source: vc
aliases: ["«FIAT»", "FIAT", "company_fiat"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fiat
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«FIAT»]]"
---
# «FIAT»

Вид компании · `company_fiat` · `common/company_types/joi_companies.txt:1137`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/fiat.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PIEDMONT`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Автомобильные заводы|Автомобильные заводы]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 1160–1162
- **attainable**: скрипт, строки 1164–1170
- **possible**: скрипт, строки 1172–1185
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы M#^m-military-formation-army-movement-speed-mult|military_formation_army_movement_speed_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.1` → [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-automobiles-mult|goods_output_automobiles_mult]] = `0.1` → [[vanilla/Товары/Автомобили|Автомобили]]
- **ai_will_do**: скрипт, строки 1193–1199
- **ai_construction_targets**: скрипт, строки 1201–1214
- **ai_weight**: скрипт, строки 1216–1218
