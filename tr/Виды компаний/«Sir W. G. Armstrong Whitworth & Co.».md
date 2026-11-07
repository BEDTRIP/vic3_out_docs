---
type: concept
description: "Вид компании ««Sir W. G. Armstrong Whitworth & Co.»» — T&R 1.13, `company_armstrong_whitworth`"
project: vic3
audience: agent
source: tr
aliases: ["«Sir W. G. Armstrong Whitworth & Co.»", "Sir W. G. Armstrong Whitworth & Co", "company_armstrong_whitworth"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_armstrong_whitworth
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_great_britain.txt]
replaces: "[[vanilla/Виды компаний/«Sir W. G. Armstrong Whitworth & Co.»]]"
---
# «Sir W. G. Armstrong Whitworth & Co.»

Вид компании · `company_armstrong_whitworth` · `common/company_types/ztr_companies_great_britain.txt:2` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **possible_prestige_goods**: изменено
- **extension_building_types**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_armstrong_whitworth.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_YORKSHIRE`
- **building_types**: [[tr/Здания/верфи|верфи]], [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **possible_prestige_goods**: `prestige_good_armstrong_ships`
- **extension_building_types**: [[tr/Здания/Aerospace Industries|Aerospace Industries]]
- **potential**: скрипт, строки 25–27
- **attainable**: скрипт, строки 29–35
- **possible**: скрипт, строки 37–48
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-ship-type-aircraft-carrier-hull-damage-mult|ship_ship_type_aircraft_carrier_hull_damage_mult]] = `0.075`
  - [[vanilla/движок/Модификаторы S#^m-ship-armor-mult|ship_armor_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 55–62
- **ai_construction_targets**: скрипт, строки 64–71
- **ai_weight**: скрипт, строки 73–75
