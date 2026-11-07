---
type: concept
description: "Вид компании «ASML» — T&R 1.13, `company_asml`"
project: vic3
source: tr
aliases: ["ASML", "company_asml"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_asml
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# ASML

Вид компании · `company_asml` · `common/company_types/ztr_tech_companies.txt:284`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/dutch_asml.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`
- **building_types**: [[tr/Здания/Robotics Industries|Robotics Industries]]
- **extension_building_types**: [[tr/Здания/Chip Foundries|Chip Foundries]]
- **possible_prestige_goods**: `prestige_good_asml_euv_lithography_machines`
- **potential**: скрипт, строки 300–302
- **attainable**: скрипт, строки 303–309
- **possible**: скрипт, строки 310–320
- **prosperity_modifier**:
  - `building_processors_foundry_throughput_add` = `0.1` → [[tr/Здания/Chip Foundries|Chip Foundries]]
  - `building_electronics_industry_throughput_add` = `0.1` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 326–332
- **ai_construction_targets**: скрипт, строки 333–340
- **ai_weight**: скрипт, строки 341–343
