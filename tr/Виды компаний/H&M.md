---
type: concept
description: "Вид компании «H&M» — T&R 1.13, `company_hm`"
project: vic3
source: tr
aliases: ["H&M", "company_hm"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_hm
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# H&M

Вид компании · `company_hm` · `common/company_types/ztr_textile_companies.txt:559`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swedish_hm.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Заводы синтетики|Заводы синтетики]]
- **extension_building_types**: [[tr/Здания/Каучуковые плантации|Каучуковые плантации]], [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **potential**: скрипт, строки 577–579
- **attainable**: скрипт, строки 580–587
- **possible**: скрипт, строки 588–598
- **prosperity_modifier**:
  - `state_pop_support_movement_feminist_mult` = `0.05`
  - `building_textile_mill_throughput_add` = `0.05` → [[tr/Здания/Текстильные фабрики|Текстильные фабрики]]
  - `state_migration_pull_mult` = `0.05`
- **ai_will_do**: скрипт, строки 604–610
- **ai_construction_targets**: скрипт, строки 611–618
- **ai_weight**: скрипт, строки 619–621
