---
type: concept
description: "Вид компании «Takeda Pharmaceuticals» — T&R 1.13, `company_takeda_pharmaceutical`"
project: vic3
source: tr
aliases: ["Takeda Pharmaceuticals", "company_takeda_pharmaceutical"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_takeda_pharmaceutical
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# Takeda Pharmaceuticals

Вид компании · `company_takeda_pharmaceutical` · `common/company_types/ztr_pharma_companies.txt:354`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_takeda.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **potential**: скрипт, строки 364–366
- **attainable**: скрипт, строки 367–373
- **possible**: скрипт, строки 374–384
- **prosperity_modifier**:
  - `building_chemical_plant_throughput_add` = `0.05` → [[tr/Здания/Заводы удобрений|Заводы удобрений]]
  - `country_institution_cost_institution_health_system_mult` = `-0.25`
  - `country_prestige_mult` = `0.05`
- **ai_will_do**: скрипт, строки 390–396
- **ai_construction_targets**: скрипт, строки 397–404
- **ai_weight**: скрипт, строки 405–407
