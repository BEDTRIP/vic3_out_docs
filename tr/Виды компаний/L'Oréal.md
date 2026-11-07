---
type: concept
description: "Вид компании «L'Oréal» — T&R 1.13, `company_oreal`"
project: vic3
source: tr
aliases: ["L'Oréal", "company_oreal"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_oreal
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_cosmetics_companies.txt]
---
# L'Oréal

Вид компании · `company_oreal` · `common/company_types/ztr_cosmetics_companies.txt:8`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_oreal.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Заводы синтетики|Заводы синтетики]], [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]], [[tr/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_cosmetics`
- **prestige_goods_trigger**: скрипт, строки 29–34
- **potential**: скрипт, строки 35–37
- **attainable**: скрипт, строки 38–45
- **possible**: скрипт, строки 46–56
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-chemical-plant-throughput-add|building_chemical_plant_throughput_add]] = `0.05` → [[tr/Здания/Заводы удобрений|Заводы удобрений]]
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-feminist-mult|state_pop_support_movement_feminist_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 62–68
- **ai_construction_targets**: скрипт, строки 69–76
- **ai_weight**: скрипт, строки 77–79
