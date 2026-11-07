---
type: concept
description: "Вид компании «AstraZeneca» — T&R 1.13, `company_astrazeneca`"
project: vic3
source: tr
aliases: ["AstraZeneca", "company_astrazeneca"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_astrazeneca
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# AstraZeneca

Вид компании · `company_astrazeneca` · `common/company_types/ztr_pharma_companies.txt:410`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swedish_astrazeneca.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EAST_ANGLIA`, `STATE_SVEALAND`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **potential**: скрипт, строки 421–426
- **attainable**: скрипт, строки 427–436
- **possible**: скрипт, строки 437–450
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `5`
  - [[vanilla/движок/Модификаторы B#^m-building-glassworks-throughput-add|building_glassworks_throughput_add]] = `0.05` → [[tr/Здания/Стеклозаводы|Стеклозаводы]]
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 456–465
- **ai_construction_targets**: скрипт, строки 466–476
- **ai_weight**: скрипт, строки 477–479
