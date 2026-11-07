---
type: concept
description: "Вид компании «Novo Nordisk» — T&R 1.13, `company_novo_nordisk`"
project: vic3
source: tr
aliases: ["Novo Nordisk", "company_novo_nordisk"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_novo_nordisk
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# Novo Nordisk

Вид компании · `company_novo_nordisk` · `common/company_types/ztr_pharma_companies.txt:600`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/danish_novo_nordisk.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZEALAND`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]], [[tr/Здания/Заводы удобрений|Заводы удобрений]]
- **potential**: скрипт, строки 611–613
- **attainable**: скрипт, строки 614–620
- **possible**: скрипт, строки 621–631
- **prosperity_modifier**:
  - `building_food_industry_throughput_add` = `0.05` → [[tr/Здания/Пищевые производства|Пищевые производства]]
  - `building_throughput_add` = `0.02`
  - `country_institution_cost_institution_health_system_mult` = `-0.25`
- **ai_will_do**: скрипт, строки 637–643
- **ai_construction_targets**: скрипт, строки 644–651
- **ai_weight**: скрипт, строки 652–654
