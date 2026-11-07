---
type: concept
description: "Вид компании «Cohere» — T&R 1.13, `company_cohere`"
project: vic3
source: tr
aliases: ["Cohere", "company_cohere"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_cohere
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Cohere

Вид компании · `company_cohere` · `common/company_types/ztr_tech_companies.txt:1004`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/canadian_cohere.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ONTARIO`
- **building_types**: [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Datacenters|Datacenters]]
- **potential**: скрипт, строки 1015–1017
- **attainable**: скрипт, строки 1018–1024
- **possible**: скрипт, строки 1025–1038
- **prosperity_modifier**:
  - `building_computer_assembly_plant_throughput_add` = `0.05` → [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 1043–1049
- **ai_construction_targets**: скрипт, строки 1050–1057
- **ai_weight**: скрипт, строки 1058–1060
