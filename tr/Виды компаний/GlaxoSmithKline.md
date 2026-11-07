---
type: concept
description: "Вид компании «GlaxoSmithKline» — T&R 1.13, `company_glaxosmithkline`"
project: vic3
source: tr
aliases: ["GlaxoSmithKline", "company_glaxosmithkline"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_glaxosmithkline
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# GlaxoSmithKline

Вид компании · `company_glaxosmithkline` · `common/company_types/ztr_pharma_companies.txt:125`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/british_glaxosmithkline.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **potential**: скрипт, строки 135–137
- **attainable**: скрипт, строки 138–144
- **possible**: скрипт, строки 145–155
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.05` → [[tr/Здания/Заводы синтетики|Заводы синтетики]]
  - [[vanilla/движок/Модификаторы C#^m-country-institution-cost-institution-health-system-mult|country_institution_cost_institution_health_system_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 160–166
- **ai_construction_targets**: скрипт, строки 167–174
- **ai_weight**: скрипт, строки 175–177
