---
type: concept
description: "Вид компании «generic_company_basic_consulting» — T&R 1.13, `generic_company_basic_consulting`"
project: vic3
audience: agent
source: tr
aliases: ["generic_company_basic_consulting"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: generic_company_basic_consulting
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# generic_company_basic_consulting

Вид компании · `generic_company_basic_consulting` · `common/company_types/ztr_99_basic_companies.txt:459`

## Поля

- **icon**: `gfx/interface/icons/company_icons/consulting_generic_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_corporation`, `dynamic_company_type_society`
- **building_types**: [[tr/Здания/Offices|Offices]]
- **possible**: скрипт, строки 475–484
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.01`
  - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 492–501
