---
type: concept
description: "Вид компании «Electronic Arts» — T&R 1.13, `company_electronic_arts`"
project: vic3
source: tr
aliases: ["Electronic Arts", "company_electronic_arts"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_electronic_arts
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_digital_media_industry.txt]
---
# Electronic Arts

Вид компании · `company_electronic_arts` · `common/company_types/ztr_digital_media_industry.txt:584`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_electronic_arts.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **extension_building_types**: [[tr/Здания/Datacenters|Datacenters]]
- **potential**: скрипт, строки 600–602
- **attainable**: скрипт, строки 603–610
- **possible**: скрипт, строки 611–621
- **prosperity_modifier**:
  - `building_computer_assembly_plant_throughput_add` = `0.05` → [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 626–632
- **ai_construction_targets**: скрипт, строки 633–640
- **ai_weight**: скрипт, строки 641–643
