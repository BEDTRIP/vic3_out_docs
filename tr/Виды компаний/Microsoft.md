---
type: concept
description: "Вид компании «Microsoft» — T&R 1.13, `company_microsoft`"
project: vic3
source: tr
aliases: ["Microsoft", "company_microsoft"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_microsoft
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Microsoft

Вид компании · `company_microsoft` · `common/company_types/ztr_tech_companies.txt:471`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_microsoft.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WASHINGTON`, `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]], [[tr/Здания/Offices|Offices]], [[tr/Здания/Datacenters|Datacenters]]
- **extension_building_types**: [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **possible_prestige_goods**: `prestige_good_microsoft_windows`
- **potential**: скрипт, строки 491–493
- **attainable**: скрипт, строки 494–503
- **possible**: скрипт, строки 504–517
- **prosperity_modifier**:
  - `building_software_industry_throughput_add` = `0.05` → [[tr/Здания/Software Industry|Software Industry]]
  - `building_office_throughput_add` = `0.05` → [[tr/Здания/Offices|Offices]]
  - `building_processors_foundry_throughput_add` = `0.05` → [[tr/Здания/Chip Foundries|Chip Foundries]]
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 524–533
- **ai_construction_targets**: скрипт, строки 534–544
- **ai_weight**: скрипт, строки 545–547
