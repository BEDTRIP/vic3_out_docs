---
type: concept
description: "Вид компании ««Compañía de Salitres y Ferrocarril de Antofagasta»» — ваниль 1.15, `company_csfa`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Compañía de Salitres y Ferrocarril de Antofagasta»", "Compañía de Salitres y Ferrocarril de Antofagasta", "company_csfa"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_csfa
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «Compañía de Salitres y Ferrocarril de Antofagasta»

Вид компании · `company_csfa` · `common/company_types/00_companies_americas.txt:150`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/bolivia_csfa.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ANTOFAGASTA`
- **building_types**: [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **potential**: скрипт, строки 167–169
- **attainable**: скрипт, строки 171–177
- **possible**: скрипт, строки 179–187
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-mult|state_infrastructure_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-approval-add|interest_group_ig_industrialists_approval_add]] = `3`
- **ai_will_do**: скрипт, строки 194–200
- **ai_construction_targets**: скрипт, строки 202–209
- **ai_weight**: скрипт, строки 211–213
