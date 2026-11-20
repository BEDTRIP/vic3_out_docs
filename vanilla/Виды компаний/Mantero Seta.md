---
type: explanation
description: "Вид компании «Mantero Seta» — ваниль 1.15.2, `company_mantero_seta`"
project: vic3
audience: agent
source: vanilla
aliases: ["Mantero Seta", "company_mantero_seta"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mantero_seta
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Mantero Seta

Вид компании · `company_mantero_seta` · `common/company_types/00_companies_mp1.txt:1100`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_mantero_seta.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOMBARDY`
- **building_types**: [[vanilla/Здания/Плантации шёлка|Плантации шёлка]], [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_como_silk`
- **potential**: скрипт, строки 1121–1124
- **attainable**: скрипт, строки 1126–1134
- **possible**: скрипт, строки 1136–1148
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.1` → [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 1155–1160
- **ai_construction_targets**: скрипт, строки 1162–1175
- **ai_weight**: скрипт, строки 1177–1179
