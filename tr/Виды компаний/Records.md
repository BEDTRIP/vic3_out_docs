---
type: concept
description: "Вид компании «Records» — T&R 1.13, `company_basic_records_and_films`"
project: vic3
source: tr
aliases: ["Records", "company_basic_records_and_films"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_basic_records_and_films
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# Records

Вид компании · `company_basic_records_and_films` · `common/company_types/ztr_99_basic_companies.txt:505`

## Поля

- **icon**: `gfx/interface/icons/company_icons/records_and_films_generic.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_music.dds`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_syndicate`, `dynamic_company_type_corporation`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]]
- **extension_building_types**: [[tr/Здания/Entertainment Areas|Entertainment Areas]], [[tr/Здания/Instrument Workshops|Instrument Workshops]], [[tr/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_generic_records_and_films`
- **prestige_goods_trigger**: скрипт, строки 525–530
- **possible**: скрипт, строки 531–540
- **prosperity_modifier**:
  - `country_prestige_mult` = `0.05`
  - `state_loyalists_from_political_movements_mult` = `0.025`
- **ai_will_do**: скрипт, строки 545–553
