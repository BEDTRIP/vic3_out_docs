---
type: concept
description: "Вид компании ««Ilva»» — VC 1.13, `company_ilva`"
project: vic3
source: vc
aliases: ["«Ilva»", "Ilva", "company_ilva"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ilva
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Ilva»]]"
---
# «Ilva»

Вид компании · `company_ilva` · `common/company_types/joi_companies.txt:5275`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **potential**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ilva.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PIEDMONT`
- **building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Угольные шахты|Угольные шахты]]
- **extension_building_types**: [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 5297–5302
- **potential**: скрипт, строки 5304–5309
- **attainable**: скрипт, строки 5311–5317
- **possible**: скрипт, строки 5319–5329
- **prosperity_modifier**:
  - `building_railway_throughput_add` = `0.1` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - `state_building_construction_sector_max_level_add` = `5`
  - `country_construction_goods_cost_mult` = `-0.05`
- **ai_will_do**: скрипт, строки 5337–5342
- **ai_construction_targets**: скрипт, строки 5344–5351
- **ai_weight**: скрипт, строки 5353–5355
