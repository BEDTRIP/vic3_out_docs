---
type: concept
description: "Вид компании ««Ericsson»» — VC 1.15, `company_ericsson`"
project: vic3
audience: agent
source: vc
aliases: ["«Ericsson»", "Ericsson", "company_ericsson"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ericsson
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Ericsson»]]"
---
# «Ericsson»

Вид компании · `company_ericsson` · `common/company_types/joi_companies.txt:5145`

## Отличия от ваниль

- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ericsson.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[vc/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[vc/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Медные рудники|Медные рудники]]
- **possible_prestige_goods**: `prestige_good_ericsson_apparatus`
- **potential**: скрипт, строки 5166–5168
- **attainable**: скрипт, строки 5170–5176
- **possible**: скрипт, строки 5178–5188
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-mult|goods_output_telephones_mult]] = `0.1` → [[vanilla/Товары/Телефоны|Телефоны]]
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
- **ai_will_do**: скрипт, строки 5195–5201
- **ai_construction_targets**: скрипт, строки 5203–5210
- **ai_weight**: скрипт, строки 5212–5214
