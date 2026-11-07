---
type: concept
description: "Вид компании «BBC» — T&R 1.13, `company_bbc`"
project: vic3
source: tr
aliases: ["BBC", "company_bbc"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bbc
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# BBC

Вид компании · `company_bbc` · `common/company_types/ztr_comunication_companies.txt:373`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/uk_bbc.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_media.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **potential**: скрипт, строки 384–386
- **attainable**: скрипт, строки 387–393
- **possible**: скрипт, строки 394–404
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.1` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
  - `country_prestige_add` = `0.1`
  - `state_decree_cost_mult` = `-0.05`
- **ai_will_do**: скрипт, строки 410–416
- **ai_construction_targets**: скрипт, строки 417–424
- **ai_weight**: скрипт, строки 425–427
