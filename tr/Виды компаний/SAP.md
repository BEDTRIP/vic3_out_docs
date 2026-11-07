---
type: concept
description: "Вид компании «SAP» — T&R 1.13, `company_sap`"
project: vic3
source: tr
aliases: ["SAP", "company_sap"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sap
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# SAP

Вид компании · `company_sap` · `common/company_types/ztr_tech_companies.txt:551`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_sap.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAVARIA`
- **building_types**: [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Datacenters|Datacenters]]
- **extension_building_types**: [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **potential**: скрипт, строки 565–567
- **attainable**: скрипт, строки 568–574
- **possible**: скрипт, строки 575–585
- **prosperity_modifier**:
  - `building_datacenter_industry_throughput_add` = `0.2` → [[tr/Здания/Datacenters|Datacenters]]
  - `building_office_throughput_add` = `0.05` → [[tr/Здания/Offices|Offices]]
  - `country_prestige_mult` = `0.05`
- **ai_will_do**: скрипт, строки 591–597
- **ai_construction_targets**: скрипт, строки 598–605
- **ai_weight**: скрипт, строки 606–608
