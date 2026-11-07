---
type: concept
description: "Вид компании «Louis Vuitton» — T&R 1.13, `company_louis_vuitton`"
project: vic3
source: tr
aliases: ["Louis Vuitton", "company_louis_vuitton"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_louis_vuitton
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# Louis Vuitton

Вид компании · `company_louis_vuitton` · `common/company_types/ztr_textile_companies.txt:14`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_louis_vuitton.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Академии искусств|Академии искусств]], [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Заводы синтетики|Заводы синтетики]]
- **extension_building_types**: [[tr/Здания/Entertainment Areas|Entertainment Areas]], [[tr/Здания/Виноградники|Виноградники]]
- **possible_prestige_goods**: `prestige_good_french_fashion`, `prestige_good_cosmetics`
- **potential**: скрипт, строки 38–40
- **attainable**: скрипт, строки 41–48
- **possible**: скрипт, строки 49–59
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-feminist-mult|state_pop_support_movement_feminist_mult]] = `0.05`
  - `building_mendelejew_synthetic_rubber_factory_throughput_add` = `0.05` → [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
  - [[vanilla/движок/Модификаторы B#^m-building-vineyard-throughput-add|building_vineyard_throughput_add]] = `0.05` → [[tr/Здания/Виноградники|Виноградники]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 66–72
- **ai_construction_targets**: скрипт, строки 73–80
- **ai_weight**: скрипт, строки 81–83
