---
type: concept
description: "Вид компании «McKinsey & Co» — T&R 1.13, `company_mckinsey`"
project: vic3
source: tr
aliases: ["McKinsey & Co", "company_mckinsey"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mckinsey
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_consulting_firm_companies.txt]
---
# McKinsey & Co

Вид компании · `company_mckinsey` · `common/company_types/ztr_consulting_firm_companies.txt:74`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_mckinsey_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_YORK`, `STATE_ILLINOIS`
- **building_types**: [[tr/Здания/Offices|Offices]]
- **potential**: скрипт, строки 90–92
- **attainable**: скрипт, строки 93–102
- **possible**: скрипт, строки 103–116
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-efficiency-mult|state_capitalists_investment_pool_efficiency_mult]] = `0.02`
  - `building_pharmaceuticals_industry_throughput_add` = `0.05` → [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **ai_will_do**: скрипт, строки 122–131
- **ai_construction_targets**: скрипт, строки 132–142
- **ai_weight**: скрипт, строки 143–145
