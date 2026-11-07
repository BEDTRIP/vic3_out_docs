---
type: concept
description: "Вид компании «Central Railway Corporation» — LLWA 1.13, `LLWA_company_railroad`"
project: vic3
audience: agent
source: llwa
aliases: ["Central Railway Corporation", "LLWA_company_railroad"]
tags: [LLWA, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_company_railroad
paths: [llwa/common/company_types/LLWA_companies.txt]
---
# Central Railway Corporation

Вид компании · `LLWA_company_railroad` · `common/company_types/LLWA_companies.txt:201`

## Поля

- **icon**: `gfx/interface/icons/company_icons/LLWA_railroad_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **category**: `capitalist_owned`
- **flavored_company**: `no`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_corporation`
- **building_types**: [[llwa/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[llwa/Здания/Roadway|Roadway]], [[llwa/Здания/Canal Waterway|Canal Waterway]], [[llwa/Здания/Natural Waterway|Natural Waterway]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 230–232
- **attainable**:
  - `always` = `yes`
- **possible**: скрипт, строки 238–245
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-motor-industry-throughput-add|building_motor_industry_throughput_add]] = `0.05` → [[vanilla/Здания/Моторные заводы|Моторные заводы]]
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 252–263
- **ai_construction_targets**: скрипт, строки 265–273
- **ai_weight**: скрипт, строки 275–277
