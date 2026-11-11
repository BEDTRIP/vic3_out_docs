---
type: concept
description: "Вид компании ««Siemens & Halske»» — VC 1.15, `company_siemens_and_halske`"
project: vic3
audience: agent
source: vc
aliases: ["«Siemens & Halske»", "Siemens & Halske", "company_siemens_and_halske"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_siemens_and_halske
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Siemens & Halske»]]"
---
# «Siemens & Halske»

Вид компании · `company_siemens_and_halske` · `common/company_types/joi_companies.txt:1815`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: добавлено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_siemens_halske.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRANDENBURG`, `STATE_BAVARIA`
- **building_types**: [[vc/Здания/Электрозаводы|Электрозаводы]], [[vanilla/Здания/Электростанции|Электростанции]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_zeiger_telegraph`
- **potential**: скрипт, строки 1837–1839
- **attainable**: скрипт, строки 1841–1847
- **possible**: скрипт, строки 1849–1862
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-radios-mult|goods_output_radios_mult]] = `0.15` → [[vanilla/Товары/Радио|Радио]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-mult|goods_output_telephones_mult]] = `0.25` → [[vanilla/Товары/Телефоны|Телефоны]]
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `10`
- **ai_will_do**: скрипт, строки 1870–1876
- **ai_construction_targets**: скрипт, строки 1878–1885
- **ai_weight**: скрипт, строки 1887–1889
