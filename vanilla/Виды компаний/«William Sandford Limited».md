---
type: concept
description: "Вид компании ««William Sandford Limited»» — ваниль 1.15, `company_william_sandford`"
project: vic3
audience: agent
source: vanilla
aliases: ["«William Sandford Limited»", "William Sandford Limited", "company_william_sandford"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_william_sandford
paths: [.vanillaVIC3/common/company_types/00_companies_asia.txt]
---
# «William Sandford Limited»

Вид компании · `company_william_sandford` · `common/company_types/00_companies_asia.txt:860`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/william_sandford_limited.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_SOUTH_WALES`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 881–886
- **potential**: скрипт, строки 888–890
- **attainable**: скрипт, строки 892–898
- **possible**: скрипт, строки 900–908
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.15` → [[vanilla/Здания/Железные дороги|Железные дороги]]
- **ai_will_do**: скрипт, строки 914–920
- **ai_construction_targets**: скрипт, строки 922–929
- **ai_weight**: скрипт, строки 931–933
