---
type: concept
description: "Вид компании «generic_company_basic_tech» — T&R 1.13, `generic_company_basic_tech`"
project: vic3
source: tr
aliases: ["generic_company_basic_tech"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: generic_company_basic_tech
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# generic_company_basic_tech

Вид компании · `generic_company_basic_tech` · `common/company_types/ztr_99_basic_companies.txt:360`

## Поля

- **icon**: `gfx/interface/icons/company_icons/tech_generic_icon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_corporation`
- **building_types**: [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **extension_building_types**: [[tr/Здания/Telecommunications Plants|Telecommunications Plants]], [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]], [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Chip Foundries|Chip Foundries]], [[tr/Здания/Robotics Industries|Robotics Industries]]
- **possible**: скрипт, строки 383–392
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.05` → [[tr/Здания/Электрозаводы|Электрозаводы]]
- **ai_will_do**: скрипт, строки 399–408
