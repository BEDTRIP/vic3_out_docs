---
type: concept
description: "Вид компании «Gucci» — T&R 1.13, `company_gucci`"
project: vic3
source: tr
aliases: ["Gucci", "company_gucci"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_gucci
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# Gucci

Вид компании · `company_gucci` · `common/company_types/ztr_textile_companies.txt:221`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/italian_gucci.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_TUSCANY`
- **building_types**: [[tr/Здания/Академии искусств|Академии искусств]], [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Животноводческие фермы|Животноводческие фермы]]
- **extension_building_types**: [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **possible_prestige_goods**: `prestige_good_italian_fashion`
- **potential**: скрипт, строки 239–241
- **attainable**: скрипт, строки 242–249
- **possible**: скрипт, строки 250–260
- **prosperity_modifier**:
  - `building_livestock_ranch_throughput_add` = `0.05` → [[tr/Здания/Животноводческие фермы|Животноводческие фермы]]
  - `state_pop_support_movement_feminist_mult` = `0.05`
  - `building_art_academy_throughput_add` = `0.1` → [[tr/Здания/Академии искусств|Академии искусств]]
- **ai_will_do**: скрипт, строки 266–272
- **ai_construction_targets**: скрипт, строки 273–280
- **ai_weight**: скрипт, строки 281–283
