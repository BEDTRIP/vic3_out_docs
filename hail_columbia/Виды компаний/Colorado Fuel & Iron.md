---
type: concept
description: "Вид компании «Colorado Fuel & Iron» — Hail Columbia 1.13, `company_usfp_cfi`"
project: vic3
source: hail_columbia
aliases: ["Colorado Fuel & Iron", "company_usfp_cfi"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_cfi
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# Colorado Fuel & Iron

Вид компании · `company_usfp_cfi` · `common/company_types/usfp_companies.txt:631`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_cfi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_COLORADO`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **potential**: скрипт, строки 649–655
- **possible**: скрипт, строки 657–677
- **prosperity_modifier**:
  - `building_coal_mine_throughput_add` = `0.10` → [[vanilla/Здания/Угольные шахты|Угольные шахты]]
  - `building_iron_mine_throughput_add` = `0.10` → [[vanilla/Здания/Железные рудники|Железные рудники]]
  - `interest_group_ig_industrialists_pol_str_mult` = `0.20`
  - `state_radicals_from_political_movements_mult` = `0.10`
- **ai_will_do**: скрипт, строки 686–705
- **ai_construction_targets**: скрипт, строки 707–714
- **ai_weight**: скрипт, строки 716–718
