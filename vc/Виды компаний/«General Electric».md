---
type: concept
description: "Вид компании ««General Electric»» — VC 1.13, `company_general_electric`"
project: vic3
source: vc
aliases: ["«General Electric»", "General Electric", "company_general_electric"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_general_electric
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«General Electric»]]"
---
# «General Electric»

Вид компании · `company_general_electric` · `common/company_types/joi_companies.txt:4967`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_general_electric.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MASSACHUSETTS`, `STATE_NEW_YORK`
- **building_types**: [[vc/Здания/Электрозаводы|Электрозаводы]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_radiola_radios`
- **potential**: скрипт, строки 4988–4990
- **attainable**: скрипт, строки 4992–5001
- **possible**: скрипт, строки 5003–5016
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-mult|goods_output_electricity_mult]] = `0.15` → [[vanilla/Товары/Электричество|Электричество]]
  - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.1` → [[vc/Здания/Электрозаводы|Электрозаводы]]
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 5024–5033
- **ai_construction_targets**: скрипт, строки 5035–5046
- **ai_weight**: скрипт, строки 5048–5050
