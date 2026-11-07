---
type: concept
description: "Вид компании «Overland Transport Trust» — LLWA 1.13, `LLWA_company_turnpike`"
project: vic3
source: llwa
aliases: ["Overland Transport Trust", "LLWA_company_turnpike"]
tags: [LLWA, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_company_turnpike
paths: [llwa/common/company_types/LLWA_companies.txt]
---
# Overland Transport Trust

Вид компании · `LLWA_company_turnpike` · `common/company_types/LLWA_companies.txt:1`

## Поля

- **icon**: `gfx/interface/icons/company_icons/LLWA_overland_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/LLWA_comp_illu_roads.dds`
- **category**: `shopkeeper_owned`
- **flavored_company**: `no`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_guild`
- **building_types**: [[llwa/Здания/Roadway|Roadway]], [[llwa/Здания/Canal Waterway|Canal Waterway]], [[llwa/Здания/Natural Waterway|Natural Waterway]]
- **extension_building_types**: [[llwa/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 30–32
- **attainable**:
  - `always` = `yes`
- **possible**: скрипт, строки 38–49
- **prosperity_modifier**:
  - `state_infrastructure_from_population_mult` = `0.05`
  - `state_infrastructure_from_population_max_mult` = `0.05`
- **ai_will_do**: скрипт, строки 56–70
- **ai_construction_targets**: скрипт, строки 72–94
- **ai_weight**: скрипт, строки 96–98
