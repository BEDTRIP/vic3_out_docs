---
type: concept
description: "Вид компании «Bayer» — T&R 1.13, `company_bayer`"
project: vic3
source: tr
aliases: ["Bayer", "company_bayer"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bayer
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# Bayer

Вид компании · `company_bayer` · `common/company_types/ztr_pharma_companies.txt:295`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_bayer.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NORTH_RHINE`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **extension_building_types**: [[tr/Здания/Hydroponic Farms|Hydroponic Farms]]
- **potential**: скрипт, строки 308–310
- **attainable**: скрипт, строки 311–317
- **possible**: скрипт, строки 318–328
- **prosperity_modifier**:
  - `building_pharmaceuticals_industry_throughput_add` = `0.05` → [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
  - `building_synthetics_plant_throughput_add` = `0.05` → [[tr/Здания/Заводы синтетики|Заводы синтетики]]
  - `country_institution_cost_institution_health_system_mult` = `-0.25`
- **ai_will_do**: скрипт, строки 334–340
- **ai_construction_targets**: скрипт, строки 341–348
- **ai_weight**: скрипт, строки 349–351
