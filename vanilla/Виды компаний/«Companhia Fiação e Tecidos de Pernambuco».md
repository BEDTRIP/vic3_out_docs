---
type: concept
description: "Вид компании ««Companhia Fiação e Tecidos de Pernambuco»» — ваниль 1.15, `company_pernambuco_textiles`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Companhia Fiação e Tecidos de Pernambuco»", "Companhia Fiação e Tecidos de Pernambuco", "company_pernambuco_textiles"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_pernambuco_textiles
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Companhia Fiação e Tecidos de Pernambuco»

Вид компании · `company_pernambuco_textiles` · `common/company_types/00_companies_cots.txt:166`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_companhia_fiacai_e_tecidos_de_pernambuco.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PERNAMBUCO`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 187–192
- **potential**: скрипт, строки 194–197
- **attainable**: скрипт, строки 199–205
- **possible**: скрипт, строки 207–214
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-cotton-plantation-throughput-add|building_cotton_plantation_throughput_add]] = `0.1` → [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
  - [[vanilla/движок/Модификаторы B#^m-building-rubber-plantation-throughput-add|building_rubber_plantation_throughput_add]] = `0.05` → [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]]
- **ai_will_do**: скрипт, строки 221–226
- **ai_construction_targets**: скрипт, строки 228–235
- **ai_weight**: скрипт, строки 237–239
