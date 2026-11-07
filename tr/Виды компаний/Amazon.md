---
type: concept
description: "Вид компании «Amazon» — T&R 1.13, `company_amazon`"
project: vic3
audience: agent
source: tr
aliases: ["Amazon", "company_amazon"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_amazon
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_ecommerce_companies.txt]
---
# Amazon

Вид компании · `company_amazon` · `common/company_types/ztr_ecommerce_companies.txt:85`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_amazon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_e_commerce.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WASHINGTON`, `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/E-Commerce Logistic Centers|E-Commerce Logistic Centers]], [[tr/Здания/Datacenters|Datacenters]], [[tr/Здания/Robotics Industries|Robotics Industries]]
- **extension_building_types**: [[tr/Здания/Электрозаводы|Электрозаводы]], [[tr/Здания/Hydroponic Farms|Hydroponic Farms]]
- **potential**: скрипт, строки 108–110
- **attainable**: скрипт, строки 112–122
- **possible**: скрипт, строки 124–137
- **prosperity_modifier**:
  - `building_software_industry_throughput_add` = `0.05` → [[tr/Здания/Software Industry|Software Industry]]
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.05` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
  - `building_office_throughput_add` = `0.05` → [[tr/Здания/Offices|Offices]]
  - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-mult|state_trade_capacity_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 146–155
- **ai_construction_targets**: скрипт, строки 157–167
- **ai_weight**: скрипт, строки 169–171
