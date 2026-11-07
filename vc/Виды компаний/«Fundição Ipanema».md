---
type: concept
description: "Вид компании ««Fundição Ipanema»» — VC 1.13, `company_fundicao_ipanema`"
project: vic3
source: vc
aliases: ["«Fundição Ipanema»", "Fundição Ipanema", "company_fundicao_ipanema"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fundicao_ipanema
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Fundição Ipanema»]]"
---
# «Fundição Ipanema»

Вид компании · `company_fundicao_ipanema` · `common/company_types/joi_companies.txt:8606`

## Отличия от ваниль

- **building_types**: изменено
- **potential**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_construction_targets**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_fundicao_ipanema.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SAO_PAULO`
- **building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **potential**: скрипт, строки 8628–8632
- **attainable**: скрипт, строки 8634–8640
- **possible**: скрипт, строки 8642–8655
- **prosperity_modifier**:
  - `building_steel_mill_throughput_add` = `0.1` → [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
  - `building_arms_industry_throughput_add` = `0.1` → [[vc/Здания/Оружейные заводы|Оружейные заводы]]
  - `goods_output_iron_mult` = `0.25` → [[vanilla/Товары/Железо|Железо]]
- **ai_will_do**: скрипт, строки 8663–8668
- **ai_construction_targets**: скрипт, строки 8670–8683
- **ai_weight**: скрипт, строки 8685–8687
