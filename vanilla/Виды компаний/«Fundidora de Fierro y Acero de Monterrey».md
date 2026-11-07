---
type: concept
description: "Вид компании ««Fundidora de Fierro y Acero de Monterrey»» — ваниль 1.13, `company_fundidora_monterrey`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Fundidora de Fierro y Acero de Monterrey»", "Fundidora de Fierro y Acero de Monterrey", "company_fundidora_monterrey"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fundidora_monterrey
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «Fundidora de Fierro y Acero de Monterrey»

Вид компании · `company_fundidora_monterrey` · `common/company_types/00_companies_americas.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/fundidora_monterrey.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RIO_GRANDE`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 23–28
- **potential**: скрипт, строки 30–32
- **attainable**: скрипт, строки 34–40
- **possible**: скрипт, строки 42–52
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.05` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы B#^m-building-iron-mine-throughput-add|building_iron_mine_throughput_add]] = `0.1` → [[vanilla/Здания/Железные рудники|Железные рудники]]
- **ai_will_do**: скрипт, строки 59–64
- **ai_construction_targets**: скрипт, строки 66–73
- **ai_weight**: скрипт, строки 75–77
