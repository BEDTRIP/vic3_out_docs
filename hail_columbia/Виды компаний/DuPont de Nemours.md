---
type: concept
description: "Вид компании «DuPont de Nemours» — Hail Columbia 1.13, `company_usfp_dupont`"
project: vic3
source: hail_columbia
aliases: ["DuPont de Nemours", "company_usfp_dupont"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_dupont
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# DuPont de Nemours

Вид компании · `company_usfp_dupont` · `common/company_types/usfp_companies.txt:164`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_dupont.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_DELAWARE`
- **building_types**: [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **extension_building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_generic_explosives`
- **prestige_goods_trigger**: скрипт, строки 186–191
- **potential**: скрипт, строки 193–199
- **possible**: скрипт, строки 201–216
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-spread-mult|country_production_tech_spread_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 223–227
- **ai_construction_targets**: скрипт, строки 229–236
- **ai_weight**: скрипт, строки 238–240
