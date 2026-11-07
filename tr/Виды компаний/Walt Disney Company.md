---
type: concept
description: "Вид компании «Walt Disney Company» — T&R 1.13, `company_disney`"
project: vic3
source: tr
aliases: ["Walt Disney Company", "company_disney"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_disney
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Walt Disney Company

Вид компании · `company_disney` · `common/company_types/ztr_comunication_companies.txt:611`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/usa_disney.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_media.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]], [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **possible_prestige_goods**: `prestige_good_generic_records_and_films`
- **prestige_goods_trigger**: скрипт, строки 626–631
- **potential**: скрипт, строки 632–634
- **attainable**: скрипт, строки 635–641
- **possible**: скрипт, строки 642–652
- **prosperity_modifier**:
  - `goods_output_elgar_music_mult` = `0.05` → [[tr/Товары/Entertainment|Entertainment]]
  - `country_influence_mult` = `0.2`
  - `state_decree_cost_mult` = `-0.1`
- **ai_will_do**: скрипт, строки 658–664
- **ai_construction_targets**: скрипт, строки 665–672
- **ai_weight**: скрипт, строки 673–675
