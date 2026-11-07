---
type: concept
description: "Вид компании «Carnegie Steel Company» — VC 1.13, `company_us_steel`"
project: vic3
audience: agent
source: vc
aliases: ["Carnegie Steel Company", "company_us_steel"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_us_steel
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Carnegie Steel Company]]"
---
# Carnegie Steel Company

Вид компании · `company_us_steel` · `common/company_types/joi_companies.txt:1893`

## Отличия от ваниль

- **possible_prestige_goods**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_carnegie_steel.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PENNSYLVANIA`
- **building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Угольные шахты|Угольные шахты]]
- **extension_building_types**: [[vanilla/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_us_steel`
- **potential**: скрипт, строки 1915–1917
- **attainable**: скрипт, строки 1919–1925
- **possible**: скрипт, строки 1927–1937
- **prosperity_modifier**:
  - `state_building_construction_sector_max_level_add` = `5`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-steel-mult|goods_output_steel_mult]] = `0.1` → [[vanilla/Товары/Сталь|Сталь]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-steamers-mult|goods_output_steamers_mult]] = `0.1` → [[vanilla/Товары/Пароходы|Пароходы]]
- **ai_will_do**: скрипт, строки 1945–1951
- **ai_construction_targets**: скрипт, строки 1953–1960
- **ai_weight**: скрипт, строки 1962–1964
