---
type: concept
description: "Вид компании ««Murano Lux»» — Morgenröte 1.13, `company_compagnia_di_venezia_e_murano`"
project: vic3
audience: agent
source: morgenrote
aliases: ["«Murano Lux»", "Murano Lux", "company_compagnia_di_venezia_e_murano"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_compagnia_di_venezia_e_murano
paths: [Morgenrote/common/company_types/mr_company_types.txt]
---
# «Murano Lux»

Вид компании · `company_compagnia_di_venezia_e_murano` · `common/company_types/mr_company_types.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/mr_glas_murano_lux.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_VENETIA`
- **building_types**: [[vanilla/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[vanilla/Здания/Мебельные фабрики|Мебельные фабрики]]
- **possible_prestige_goods**: `prestige_good_murano_glass`
- **potential**: скрипт, строки 23–27
- **attainable**: скрипт, строки 29–35
- **possible**: скрипт, строки 37–46
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-glassworks-throughput-add|building_glassworks_throughput_add]] = `0.1` → [[vanilla/Здания/Стеклозаводы|Стеклозаводы]]
  - [[vanilla/движок/Модификаторы S#^m-state-upper-strata-standard-of-living-add|state_upper_strata_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 53–58
- **ai_construction_targets**: скрипт, строки 60–67
- **ai_weight**: скрипт, строки 69–71
