---
type: concept
description: "Вид компании «Intel» — T&R 1.13, `company_intel`"
project: vic3
source: tr
aliases: ["Intel", "company_intel"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_intel
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Intel

Вид компании · `company_intel` · `common/company_types/ztr_tech_companies.txt:223`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_intel.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Electronic Components Industries|Electronic Components Industries]], [[tr/Здания/Chip Foundries|Chip Foundries]]
- **possible_prestige_goods**: `prestige_good_intel_processors`
- **potential**: скрипт, строки 237–239
- **attainable**: скрипт, строки 240–246
- **possible**: скрипт, строки 247–257
- **prosperity_modifier**:
  - `building_computer_assembly_plant_throughput_add` = `0.1` → [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
  - `building_datacenter_industry_throughput_add` = `0.05` → [[tr/Здания/Datacenters|Datacenters]]
  - `building_software_industry_throughput_add` = `0.1` → [[tr/Здания/Software Industry|Software Industry]]
- **ai_will_do**: скрипт, строки 263–269
- **ai_construction_targets**: скрипт, строки 270–277
- **ai_weight**: скрипт, строки 278–280
