---
type: explanation
description: "Вид компании «Carnegie Steel Company» — ваниль 1.15.2, `company_us_steel`"
project: vic3
audience: agent
source: vanilla
aliases: ["Carnegie Steel Company", "company_us_steel"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_us_steel
paths: [.vanillaVIC3/common/company_types/00_companies_usa.txt]
---
# Carnegie Steel Company

Вид компании · `company_us_steel` · `common/company_types/00_companies_usa.txt:170`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_carnegie_steel.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PENNSYLVANIA`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **extension_building_types**: [[vanilla/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 192–197
- **potential**: скрипт, строки 199–201
- **attainable**: скрипт, строки 203–209
- **possible**: скрипт, строки 211–223
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.1` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.1` → [[vanilla/Здания/Верфи|Верфи]]
- **ai_will_do**: скрипт, строки 230–236
- **ai_construction_targets**: скрипт, строки 238–245
- **ai_weight**: скрипт, строки 247–249
