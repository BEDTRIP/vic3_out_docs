---
type: concept
description: "Вид компании ««Ford Motor Company»» — VC 1.15, `company_ford_motor`"
project: vic3
audience: agent
source: vc
aliases: ["«Ford Motor Company»", "Ford Motor Company", "company_ford_motor"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ford_motor
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Ford Motor Company»]]"
---
# «Ford Motor Company»

Вид компании · `company_ford_motor` · `common/company_types/joi_companies.txt:159`

## Отличия от ваниль

- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_ford.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MICHIGAN`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Каучуковые плантации|Каучуковые плантации]]
- **possible_prestige_goods**: `prestige_good_ford_automobiles`
- **potential**: скрипт, строки 181–183
- **attainable**: скрипт, строки 185–191
- **possible**: скрипт, строки 193–203
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-military-goods-cost-mult|country_military_goods_cost_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы M#^m-military-formation-army-movement-speed-mult|military_formation_army_movement_speed_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-automobiles-mult|goods_output_automobiles_mult]] = `0.15` → [[vanilla/Товары/Автомобили|Автомобили]]
- **ai_will_do**: скрипт, строки 211–217
- **ai_construction_targets**: скрипт, строки 219–226
- **ai_weight**: скрипт, строки 228–230
