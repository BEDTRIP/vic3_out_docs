---
type: concept
description: "Вид компании ««Standard Oil»» — ваниль 1.13, `company_standard_oil`"
project: vic3
source: vanilla
aliases: ["«Standard Oil»", "Standard Oil", "company_standard_oil"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_standard_oil
paths: [.vanillaVIC3/common/company_types/00_companies_usa.txt]
---
# «Standard Oil»

Вид компании · `company_standard_oil` · `common/company_types/00_companies_usa.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_standard_oil.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Буровые вышки|Буровые вышки]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]]
- **potential**: скрипт, строки 17–19
- **attainable**: скрипт, строки 21–27
- **possible**: скрипт, строки 29–39
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.2` → [[vanilla/Здания/Железные дороги|Железные дороги]]
- **ai_will_do**: скрипт, строки 45–52
- **ai_construction_targets**: скрипт, строки 54–62
- **ai_weight**: скрипт, строки 64–66
