---
type: concept
description: "Вид компании ««Lilpop, Rau i Loewenstein»» — VC 1.13, `company_lilpop`"
project: vic3
source: vc
aliases: ["«Lilpop, Rau i Loewenstein»", "Lilpop, Rau i Loewenstein", "company_lilpop"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lilpop
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Lilpop, Rau i Loewenstein»]]"
---
# «Lilpop, Rau i Loewenstein»

Вид компании · `company_lilpop` · `common/company_types/joi_companies.txt:8277`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **possible_prestige_goods**: изменено
- **prosperity_modifier**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/polish_lilpop.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BOHEMIA`, `STATE_NORTH_RHINE`, `STATE_MAZOVIA`, `STATE_GREATER_POLAND`
- **building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_tools`
- **potential**: скрипт, строки 8299–8301
- **attainable**: скрипт, строки 8303–8312
- **possible**: скрипт, строки 8314–8327
- **prosperity_modifier**:
  - `building_coal_mine_throughput_add` = `0.1` → [[vc/Здания/Угольные шахты|Угольные шахты]]
  - `building_iron_mine_throughput_add` = `0.1` → [[vc/Здания/Железные рудники|Железные рудники]]
  - `goods_output_tools_mult` = `0.05` → [[vanilla/Товары/Инструменты|Инструменты]]
- **ai_will_do**: скрипт, строки 8335–8344
- **ai_construction_targets**: скрипт, строки 8346–8357
- **ai_weight**: скрипт, строки 8359–8361
