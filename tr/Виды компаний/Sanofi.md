---
type: concept
description: "Вид компании «Sanofi» — T&R 1.13, `company_sanofi`"
project: vic3
source: tr
aliases: ["Sanofi", "company_sanofi"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sanofi
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# Sanofi

Вид компании · `company_sanofi` · `common/company_types/ztr_pharma_companies.txt:238`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_sanofi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **potential**: скрипт, строки 248–250
- **attainable**: скрипт, строки 251–257
- **possible**: скрипт, строки 258–268
- `<`
- **prosperity_modifier**:
  - `building_synthetics_plant_throughput_add` = `0.05` → [[tr/Здания/Заводы синтетики|Заводы синтетики]]
  - `building_mendelejew_synthetic_rubber_factory_throughput_add` = `0.05` → [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
  - `country_institution_cost_institution_health_system_mult` = `-0.25`
- **ai_will_do**: скрипт, строки 275–281
- **ai_construction_targets**: скрипт, строки 282–289
- **ai_weight**: скрипт, строки 290–292
