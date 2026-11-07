---
type: concept
description: "Вид компании «Deloitte» — T&R 1.13, `company_deloitte`"
project: vic3
audience: agent
source: tr
aliases: ["Deloitte", "company_deloitte"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_deloitte
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_consulting_firm_companies.txt]
---
# Deloitte

Вид компании · `company_deloitte` · `common/company_types/ztr_consulting_firm_companies.txt:11`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/english_deloitte_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Offices|Offices]]
- **potential**: скрипт, строки 25–27
- **attainable**: скрипт, строки 28–34
- **possible**: скрипт, строки 35–45
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `0.1`
  - `building_pharmaceuticals_industry_throughput_add` = `0.05` → [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `-0.15`
- **ai_will_do**: скрипт, строки 51–57
- **ai_construction_targets**: скрипт, строки 58–65
- **ai_weight**: скрипт, строки 66–68
