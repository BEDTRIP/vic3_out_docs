---
type: concept
description: "Вид компании ««Lilpop, Rau i Loewenstein»» — ваниль 1.13, `company_lilpop`"
project: vic3
source: vanilla
aliases: ["«Lilpop, Rau i Loewenstein»", "Lilpop, Rau i Loewenstein", "company_lilpop"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lilpop
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Lilpop, Rau i Loewenstein»

Вид компании · `company_lilpop` · `common/company_types/00_companies_europe.txt:1020`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/polish_lilpop.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MAZOVIA`, `STATE_GREATER_POLAND`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 1042–1047
- **potential**: скрипт, строки 1049–1051
- **attainable**: скрипт, строки 1053–1062
- **possible**: скрипт, строки 1064–1077
- **prosperity_modifier**:
  - `building_motor_industry_throughput_add` = `0.1` → [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **ai_will_do**: скрипт, строки 1083–1092
- **ai_construction_targets**: скрипт, строки 1094–1105
- **ai_weight**: скрипт, строки 1107–1109
