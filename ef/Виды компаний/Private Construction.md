---
type: concept
description: "Вид компании «Private Construction» — E&F 1.13, `company_private_construction`"
project: vic3
audience: agent
source: ef
aliases: ["Private Construction", "company_private_construction"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_private_construction
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Private Construction

Вид компании · `company_private_construction` · `common/company_types/00_ef_companies.txt:6647`

## Поля

- **icon**: `gfx/interface/icons/company_icons/company_private_construction.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **replaces_company**: `company_private_construction`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_consortium`, `dynamic_company_type_corporation`, `dynamic_company_type_conglomerate`, `dynamic_company_type_syndicate`, `dynamic_company_type_combine`
- **possible_prestige_goods**: `manufacture_stock_construction`
- **building_types**: [[ef/Здания/Private Construction Sector|Private Construction Sector]]
- **possible**: скрипт, строки 6673–6679
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.025`
