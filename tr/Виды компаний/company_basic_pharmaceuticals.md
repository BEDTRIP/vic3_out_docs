---
type: concept
description: "Вид компании «company_basic_pharmaceuticals» — T&R 1.13, `company_basic_pharmaceuticals`"
project: vic3
audience: agent
source: tr
aliases: ["company_basic_pharmaceuticals"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_basic_pharmaceuticals
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# company_basic_pharmaceuticals

Вид компании · `company_basic_pharmaceuticals` · `common/company_types/ztr_99_basic_companies.txt:306`

## Поля

- **icon**: `gfx/interface/icons/company_icons/pharma_generic_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `no`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_consortium`, `dynamic_company_type_corporation`, `dynamic_company_type_conglomerate`, `dynamic_company_type_syndicate`, `dynamic_company_type_combine`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **extension_building_types**: [[tr/Здания/Заводы синтетики|Заводы синтетики]]
- **possible**: скрипт, строки 331–340
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.01`
  - [[vanilla/движок/Модификаторы C#^m-country-institution-cost-institution-health-system-mult|country_institution_cost_institution_health_system_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 347–356
