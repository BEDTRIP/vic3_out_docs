---
type: concept
description: "Вид компании ««Empresas Eléctricas Asociadas»» — ваниль 1.13, `company_eea`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Empresas Eléctricas Asociadas»", "Empresas Eléctricas Asociadas", "company_eea"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_eea
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Empresas Eléctricas Asociadas»

Вид компании · `company_eea` · `common/company_types/00_companies_cots.txt:754`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/peru_empresas_electricas_asociadas.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LIMA`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **potential**: скрипт, строки 770–773
- **attainable**: скрипт, строки 775–781
- **possible**: скрипт, строки 783–793
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-mult|state_infrastructure_from_population_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 800–806
- **ai_construction_targets**: скрипт, строки 808–815
- **ai_weight**: скрипт, строки 817–819
