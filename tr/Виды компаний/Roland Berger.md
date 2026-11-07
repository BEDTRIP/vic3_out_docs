---
type: concept
description: "Вид компании «Roland Berger» — T&R 1.13, `company_roland_berger`"
project: vic3
source: tr
aliases: ["Roland Berger", "company_roland_berger"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_roland_berger
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_consulting_firm_companies.txt]
---
# Roland Berger

Вид компании · `company_roland_berger` · `common/company_types/ztr_consulting_firm_companies.txt:151`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_roland_berger_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAVARIA`
- **building_types**: [[tr/Здания/Offices|Offices]]
- **potential**: скрипт, строки 166–168
- **attainable**: скрипт, строки 169–175
- **possible**: скрипт, строки 176–186
- **prosperity_modifier**:
  - `building_motor_industry_throughput_add` = `0.05` → [[tr/Здания/Моторные заводы|Моторные заводы]]
  - `building_chemical_plant_throughput_add` = `0.05` → [[tr/Здания/Заводы удобрений|Заводы удобрений]]
  - `country_bureaucracy_investment_cost_factor_mult` = `-0.1`
- **ai_will_do**: скрипт, строки 192–198
- **ai_construction_targets**: скрипт, строки 199–206
- **ai_weight**: скрипт, строки 207–209
