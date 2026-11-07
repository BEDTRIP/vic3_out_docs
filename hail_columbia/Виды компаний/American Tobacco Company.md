---
type: concept
description: "Вид компании «American Tobacco Company» — Hail Columbia 1.13, `company_usfp_american_tobacco`"
project: vic3
source: hail_columbia
aliases: ["American Tobacco Company", "company_usfp_american_tobacco"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_american_tobacco
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# American Tobacco Company

Вид компании · `company_usfp_american_tobacco` · `common/company_types/usfp_companies.txt:392`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_american_tobacco.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NORTH_CAROLINA`
- **building_types**: [[vanilla/Здания/Табачные плантации|Табачные плантации]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]]
- **potential**: скрипт, строки 413–419
- **possible**: скрипт, строки 421–431
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-tobacco-plantation-throughput-add|building_tobacco_plantation_throughput_add]] = `0.15` → [[vanilla/Здания/Табачные плантации|Табачные плантации]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 438–447
- **ai_construction_targets**: скрипт, строки 449–456
- **ai_weight**: скрипт, строки 458–460
