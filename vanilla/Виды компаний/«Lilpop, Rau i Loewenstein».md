---
type: explanation
description: "Вид компании ««Lilpop, Rau i Loewenstein»» — ваниль 1.15.2, `company_lilpop`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Lilpop, Rau i Loewenstein»", "Lilpop, Rau i Loewenstein", "company_lilpop"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lilpop
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Lilpop, Rau i Loewenstein»

Вид компании · `company_lilpop` · `common/company_types/00_companies_europe.txt:1029`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/polish_lilpop.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MAZOVIA`, `STATE_GREATER_POLAND`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 1051–1056
- **potential**: скрипт, строки 1058–1060
- **attainable**: скрипт, строки 1062–1071
- **possible**: скрипт, строки 1073–1086
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **ai_will_do**: скрипт, строки 1092–1101
- **ai_construction_targets**: скрипт, строки 1103–1114
- **ai_weight**: скрипт, строки 1116–1118
