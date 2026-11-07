---
type: concept
description: "Вид компании «Tokyo Electric Light Company, Ltd» — ваниль 1.13, `company_tokyo_electric_light_company`"
project: vic3
source: vanilla
aliases: ["Tokyo Electric Light Company, Ltd", "company_tokyo_electric_light_company"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_tokyo_electric_light_company
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Tokyo Electric Light Company, Ltd

Вид компании · `company_tokyo_electric_light_company` · `common/company_types/00_companies_ep2.txt:211`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_tokyo_electric_light_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 233–236
- **attainable**: скрипт, строки 238–246
- **possible**: скрипт, строки 248–259
- **prosperity_modifier**:
  - `building_electrics_industry_throughput_add` = `0.1` → [[vanilla/Здания/Электрозаводы|Электрозаводы]]
  - `building_urban_center_throughput_add` = `0.1` → [[vanilla/Здания/Городские центры|Городские центры]]
- **ai_will_do**: скрипт, строки 266–273
- **ai_construction_targets**: скрипт, строки 275–282
- **ai_weight**: скрипт, строки 284–286
