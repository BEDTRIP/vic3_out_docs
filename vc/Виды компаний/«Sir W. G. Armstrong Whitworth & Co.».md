---
type: concept
description: "Вид компании ««Sir W. G. Armstrong Whitworth & Co.»» — VC 1.13, `company_armstrong_whitworth`"
project: vic3
audience: agent
source: vc
aliases: ["«Sir W. G. Armstrong Whitworth & Co.»", "Sir W. G. Armstrong Whitworth & Co", "company_armstrong_whitworth"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_armstrong_whitworth
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Sir W. G. Armstrong Whitworth & Co.»]]"
---
# «Sir W. G. Armstrong Whitworth & Co.»

Вид компании · `company_armstrong_whitworth` · `common/company_types/joi_companies.txt:2`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **possible_prestige_goods**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_armstrong_whitworth.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_YORKSHIRE`, `STATE_ULSTER`, `STATE_MUNSTER`
- **building_types**: [[vc/Здания/верфи|верфи]], [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vc/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Порты|Порты]]
- **potential**: скрипт, строки 22–24
- **attainable**: скрипт, строки 26–32
- **possible**: скрипт, строки 34–48
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-hull-damage-mult|ship_hull_damage_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-ship-armor-mult|ship_armor_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-crew-damage-mult|ship_crew_damage_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 56–63
- **ai_construction_targets**: скрипт, строки 65–72
- **ai_weight**: скрипт, строки 74–76
