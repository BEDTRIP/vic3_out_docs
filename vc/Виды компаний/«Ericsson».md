---
type: concept
description: "Вид компании ««Ericsson»» — VC 1.13, `company_ericsson`"
project: vic3
source: vc
aliases: ["«Ericsson»", "Ericsson", "company_ericsson"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ericsson
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Ericsson»]]"
---
# «Ericsson»

Вид компании · `company_ericsson` · `common/company_types/joi_companies.txt:5144`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ericsson.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[vc/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[vc/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_ericsson_apparatus`
- **potential**: скрипт, строки 5164–5166
- **attainable**: скрипт, строки 5168–5174
- **possible**: скрипт, строки 5176–5186
- **prosperity_modifier**:
  - `goods_output_telephones_mult` = `0.1` → [[vanilla/Товары/Телефоны|Телефоны]]
  - `state_education_access_wealth_add` = `0.005`
- **ai_will_do**: скрипт, строки 5193–5199
- **ai_construction_targets**: скрипт, строки 5201–5208
- **ai_weight**: скрипт, строки 5210–5212
