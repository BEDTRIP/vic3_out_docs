---
type: concept
description: "Вид компании «Anaconda Mining Company» — Hail Columbia 1.13, `company_usfp_anaconda`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Anaconda Mining Company", "company_usfp_anaconda"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_anaconda
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# Anaconda Mining Company

Вид компании · `company_usfp_anaconda` · `common/company_types/usfp_companies.txt:310`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_anaconda.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MONTANA`
- **building_types**: [[vanilla/Здания/Золотые рудники|Золотые рудники]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **potential**: скрипт, строки 328–334
- **possible**: скрипт, строки 336–352
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `0.15`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 360–375
- **ai_construction_targets**: скрипт, строки 377–384
- **ai_weight**: скрипт, строки 386–388
