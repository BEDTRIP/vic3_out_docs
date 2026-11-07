---
type: concept
description: "Вид компании ««La Rosada»» — ваниль 1.13, `company_la_rosada`"
project: vic3
source: vanilla
aliases: ["«La Rosada»", "La Rosada", "company_la_rosada"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_la_rosada
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «La Rosada»

Вид компании · `company_la_rosada` · `common/company_types/00_companies_americas.txt:390`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/paraguay_la_rosada.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAJO_PARAGUAY`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 412–417
- **potential**: скрипт, строки 419–421
- **attainable**: скрипт, строки 423–429
- **possible**: скрипт, строки 431–441
- **prosperity_modifier**:
  - `unit_defense_mult` = `0.05`
  - `building_iron_mine_throughput_add` = `0.1` → [[vanilla/Здания/Железные рудники|Железные рудники]]
- **ai_will_do**: скрипт, строки 448–454
- **ai_construction_targets**: скрипт, строки 456–463
- **ai_weight**: скрипт, строки 465–467
