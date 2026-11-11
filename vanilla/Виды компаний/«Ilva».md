---
type: concept
description: "Вид компании ««Ilva»» — ваниль 1.15, `company_ilva`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Ilva»", "Ilva", "company_ilva"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ilva
paths: [.vanillaVIC3/common/company_types/00_companies_italy.txt]
---
# «Ilva»

Вид компании · `company_ilva` · `common/company_types/00_companies_italy.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ilva.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PIEDMONT`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 23–28
- **potential**: скрипт, строки 30–32
- **attainable**: скрипт, строки 34–40
- **possible**: скрипт, строки 42–50
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.1` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы B#^m-building-artillery-foundry-throughput-add|building_artillery_foundry_throughput_add]] = `0.05` → [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **ai_will_do**: скрипт, строки 57–62
- **ai_construction_targets**: скрипт, строки 64–71
- **ai_weight**: скрипт, строки 73–75
