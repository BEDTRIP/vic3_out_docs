---
type: concept
description: "Вид компании «Sega» — T&R 1.13, `company_sega`"
project: vic3
source: tr
aliases: ["Sega", "company_sega"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sega
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_digital_media_industry.txt]
---
# Sega

Вид компании · `company_sega` · `common/company_types/ztr_digital_media_industry.txt:335`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_sega.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **extension_building_types**: [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
- **potential**: скрипт, строки 351–353
- **attainable**: скрипт, строки 354–361
- **possible**: скрипт, строки 362–372
- **prosperity_modifier**:
  - `building_consumer_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.05`
- **ai_will_do**: скрипт, строки 377–383
- **ai_construction_targets**: скрипт, строки 384–391
- **ai_weight**: скрипт, строки 392–394
