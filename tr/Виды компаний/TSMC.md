---
type: concept
description: "Вид компании «TSMC» — T&R 1.13, `company_tsmc`"
project: vic3
source: tr
aliases: ["TSMC", "company_tsmc"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_tsmc
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# TSMC

Вид компании · `company_tsmc` · `common/company_types/ztr_tech_companies.txt:347`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/taiwanese_tsmc.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FORMOSA`
- **building_types**: [[tr/Здания/Chip Foundries|Chip Foundries]], [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]]
- **extension_building_types**: [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **possible_prestige_goods**: `prestige_good_tsmc_wafers`
- **potential**: скрипт, строки 364–366
- **attainable**: скрипт, строки 367–373
- **possible**: скрипт, строки 374–384
- **prosperity_modifier**:
  - `building_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
  - `building_electrics_industry_throughput_add` = `0.1` → [[tr/Здания/Электрозаводы|Электрозаводы]]
  - `country_prestige_mult` = `0.05`
  - `interest_group_ig_industrialists_pol_str_mult` = `0.05`
- **ai_will_do**: скрипт, строки 391–397
- **ai_construction_targets**: скрипт, строки 398–405
- **ai_weight**: скрипт, строки 406–408
