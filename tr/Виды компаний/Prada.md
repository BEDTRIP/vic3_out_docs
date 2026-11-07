---
type: concept
description: "Вид компании «Prada» — T&R 1.13, `company_prada`"
project: vic3
audience: agent
source: tr
aliases: ["Prada", "company_prada"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_prada
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# Prada

Вид компании · `company_prada` · `common/company_types/ztr_textile_companies.txt:154`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/italian_prada.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOMBARDY`
- **building_types**: [[tr/Здания/Академии искусств|Академии искусств]], [[tr/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[tr/Здания/Заводы синтетики|Заводы синтетики]], [[tr/Здания/Животноводческие фермы|Животноводческие фермы]], [[tr/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_italian_fashion`
- **potential**: скрипт, строки 173–175
- **attainable**: скрипт, строки 176–183
- **possible**: скрипт, строки 184–194
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-silk-plantation-throughput-add|building_silk_plantation_throughput_add]] = `0.1` → [[tr/Здания/Плантации шёлка|Плантации шёлка]]
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-feminist-mult|state_pop_support_movement_feminist_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.05` → [[tr/Здания/Текстильные фабрики|Текстильные фабрики]]
- **ai_will_do**: скрипт, строки 200–206
- **ai_construction_targets**: скрипт, строки 207–214
- **ai_weight**: скрипт, строки 215–217
