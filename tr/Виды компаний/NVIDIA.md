---
type: concept
description: "Вид компании «NVIDIA» — T&R 1.13, `company_nvidia`"
project: vic3
source: tr
aliases: ["NVIDIA", "company_nvidia"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nvidia
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# NVIDIA

Вид компании · `company_nvidia` · `common/company_types/ztr_tech_companies.txt:758`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_nvidia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Chip Foundries|Chip Foundries]], [[tr/Здания/Datacenters|Datacenters]]
- **extension_building_types**: [[tr/Здания/Software Industry|Software Industry]]
- **possible_prestige_goods**: `prestige_good_gpu`
- **potential**: скрипт, строки 775–777
- **attainable**: скрипт, строки 778–784
- **possible**: скрипт, строки 785–798
- **prosperity_modifier**:
  - `building_computer_assembly_plant_throughput_add` = `0.05` → [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
  - `goods_output_ai_systems_mult` = `0.05` → [[tr/Товары/AI Systems|AI Systems]]
  - `country_prestige_mult` = `0.05`
- **ai_will_do**: скрипт, строки 804–810
- **ai_construction_targets**: скрипт, строки 811–818
- **ai_weight**: скрипт, строки 819–821
