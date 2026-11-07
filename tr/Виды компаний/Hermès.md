---
type: concept
description: "Вид компании «Hermès» — T&R 1.13, `company_hermes`"
project: vic3
audience: agent
source: tr
aliases: ["Hermès", "company_hermes"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_hermes
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# Hermès

Вид компании · `company_hermes` · `common/company_types/ztr_textile_companies.txt:87`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_hermes.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Мебельные фабрики|Мебельные фабрики]], [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Академии искусств|Академии искусств]]
- **extension_building_types**: [[tr/Здания/Плантации шёлка|Плантации шёлка]], [[tr/Здания/Животноводческие фермы|Животноводческие фермы]]
- **possible_prestige_goods**: `prestige_good_french_fashion`
- **potential**: скрипт, строки 106–108
- **attainable**: скрипт, строки 109–116
- **possible**: скрипт, строки 117–127
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-feminist-mult|state_pop_support_movement_feminist_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-art-academy-throughput-add|building_art_academy_throughput_add]] = `0.1` → [[tr/Здания/Академии искусств|Академии искусств]]
  - [[vanilla/движок/Модификаторы S#^m-state-upper-strata-standard-of-living-add|state_upper_strata_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 133–139
- **ai_construction_targets**: скрипт, строки 140–147
- **ai_weight**: скрипт, строки 148–150
