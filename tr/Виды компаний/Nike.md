---
type: concept
description: "Вид компании «Nike» — T&R 1.13, `company_nike`"
project: vic3
audience: agent
source: tr
aliases: ["Nike", "company_nike"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nike
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# Nike

Вид компании · `company_nike` · `common/company_types/ztr_textile_companies.txt:418`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_nike.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_OREGON`, `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **extension_building_types**: [[tr/Здания/Каучуковые плантации|Каучуковые плантации]]
- **possible_prestige_goods**: `prestige_good_nike_shoes`
- **potential**: скрипт, строки 436–438
- **attainable**: скрипт, строки 439–449
- **possible**: скрипт, строки 450–463
- **prosperity_modifier**:
  - `building_mendelejew_synthetic_rubber_factory_throughput_add` = `0.1` → [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
  - `building_elgar_opera_throughput_add` = `0.05` → [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **ai_will_do**: скрипт, строки 468–477
- **ai_construction_targets**: скрипт, строки 478–488
- **ai_weight**: скрипт, строки 489–491
