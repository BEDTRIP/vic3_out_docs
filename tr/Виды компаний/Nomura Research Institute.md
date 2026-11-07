---
type: concept
description: "Вид компании «Nomura Research Institute» — T&R 1.13, `company_nri_nomura`"
project: vic3
source: tr
aliases: ["Nomura Research Institute", "company_nri_nomura"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nri_nomura
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_consulting_firm_companies.txt]
---
# Nomura Research Institute

Вид компании · `company_nri_nomura` · `common/company_types/ztr_consulting_firm_companies.txt:280`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_nomura_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Offices|Offices]]
- **extension_building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]], [[tr/Здания/Моторные заводы|Моторные заводы]]
- **potential**: скрипт, строки 295–297
- **attainable**: скрипт, строки 298–304
- **possible**: скрипт, строки 305–315
- **prosperity_modifier**:
  - `building_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
  - `building_motor_industry_throughput_add` = `0.05` → [[tr/Здания/Моторные заводы|Моторные заводы]]
  - `country_bureaucracy_investment_cost_factor_mult` = `-0.1`
- **ai_will_do**: скрипт, строки 321–327
- **ai_construction_targets**: скрипт, строки 328–335
- **ai_weight**: скрипт, строки 336–338
