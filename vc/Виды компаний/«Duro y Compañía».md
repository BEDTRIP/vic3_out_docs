---
type: concept
description: "Вид компании ««Duro y Compañía»» — VC 1.13, `company_duro_y_compania`"
project: vic3
source: vc
aliases: ["«Duro y Compañía»", "Duro y Compañía", "company_duro_y_compania"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_duro_y_compania
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Duro y Compañía»]]"
---
# «Duro y Compañía»

Вид компании · `company_duro_y_compania` · `common/company_types/joi_companies.txt:6722`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/spain_duro_y_compania.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ASTURIAS`
- **building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vc/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 6744–6749
- **potential**: скрипт, строки 6751–6753
- **attainable**: скрипт, строки 6755–6761
- **possible**: скрипт, строки 6763–6773
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-arms-industry-throughput-add|building_arms_industry_throughput_add]] = `0.2` → [[vc/Здания/Оружейные заводы|Оружейные заводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.2` → [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 6780–6786
- **ai_construction_targets**: скрипт, строки 6788–6795
- **ai_weight**: скрипт, строки 6797–6799
