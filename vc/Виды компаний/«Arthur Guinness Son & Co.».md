---
type: concept
description: "Вид компании ««Arthur Guinness Son & Co.»» — VC 1.15, `company_guinness`"
project: vic3
audience: agent
source: vc
aliases: ["«Arthur Guinness Son & Co.»", "Arthur Guinness Son & Co. Ltd", "company_guinness"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_guinness
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Arthur Guinness Son & Co.»]]"
---
# «Arthur Guinness Son & Co.»

Вид компании · `company_guinness` · `common/company_types/joi_companies.txt:3206`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **possible**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/arthur_guinness_son.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LANCASHIRE`, `STATE_LEINSTER`, `STATE_ULSTER`
- **building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vc/Здания/Пшеничные поля|Пшеничные поля]]
- **extension_building_types**: [[vc/Здания/Ржаные поля|Ржаные поля]], [[vc/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_guinness`
- **potential**: скрипт, строки 3228–3230
- **attainable**: скрипт, строки 3232–3238
- **possible**: скрипт, строки 3240–3250
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-violent-hostility-mult|state_radicalism_increases_violent_hostility_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-cultural-erasure-mult|state_radicalism_increases_cultural_erasure_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-open-prejudice-mult|state_radicalism_increases_open_prejudice_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 3259–3265
- **ai_construction_targets**: скрипт, строки 3267–3274
- **ai_weight**: скрипт, строки 3276–3278
