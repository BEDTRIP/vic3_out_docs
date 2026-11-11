---
type: concept
description: "Вид компании ««Philips»» — VC 1.15, `company_philips`"
project: vic3
audience: agent
source: vc
aliases: ["«Philips»", "Philips", "company_philips"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_philips
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Philips»]]"
---
# «Philips»

Вид компании · `company_philips` · `common/company_types/joi_companies.txt:5054`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **potential**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/philips.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`, `STATE_GELRE`
- **building_types**: [[vc/Здания/Электрозаводы|Электрозаводы]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_philips_chapel_radio`
- **potential**: скрипт, строки 5075–5082
- **attainable**: скрипт, строки 5084–5093
- **possible**: скрипт, строки 5095–5108
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-radios-mult|goods_output_radios_mult]] = `0.1` → [[vanilla/Товары/Радио|Радио]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-mult|goods_output_telephones_mult]] = `0.1` → [[vanilla/Товары/Телефоны|Телефоны]]
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `5`
- **ai_will_do**: скрипт, строки 5116–5125
- **ai_construction_targets**: скрипт, строки 5127–5138
- **ai_weight**: скрипт, строки 5140–5142
