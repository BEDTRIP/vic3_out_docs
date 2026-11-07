---
type: concept
description: "Вид компании «Grupo Televisa» — T&R 1.13, `company_televisa`"
project: vic3
source: tr
aliases: ["Grupo Televisa", "company_televisa"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_televisa
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Grupo Televisa

Вид компании · `company_televisa` · `common/company_types/ztr_comunication_companies.txt:494`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/mexico_televisa.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_media.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MEXICO`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **potential**: скрипт, строки 505–507
- **attainable**: скрипт, строки 508–514
- **possible**: скрипт, строки 515–525
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.05` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
  - `country_prestige_add` = `0.05`
  - `state_decree_cost_mult` = `-0.05`
- **ai_will_do**: скрипт, строки 531–537
- **ai_construction_targets**: скрипт, строки 538–545
- **ai_weight**: скрипт, строки 546–548
