---
type: concept
description: "Вид компании «Alibaba Group» — T&R 1.13, `company_alibaba`"
project: vic3
audience: agent
source: tr
aliases: ["Alibaba Group", "company_alibaba"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_alibaba
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_ecommerce_companies.txt]
---
# Alibaba Group

Вид компании · `company_alibaba` · `common/company_types/ztr_ecommerce_companies.txt:176`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_alibaba.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_e_commerce.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZHEJIANG`
- **building_types**: [[tr/Здания/E-Commerce Logistic Centers|E-Commerce Logistic Centers]], [[tr/Здания/Software Industry|Software Industry]]
- **extension_building_types**: [[tr/Здания/Datacenters|Datacenters]], [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **potential**: скрипт, строки 198–200
- **attainable**: скрипт, строки 202–208
- **possible**: скрипт, строки 210–220
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.05` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
  - `building_office_throughput_add` = `0.05` → [[tr/Здания/Offices|Offices]]
  - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-mult|state_trade_capacity_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-trade-quantity-mult|state_trade_quantity_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 229–235
- **ai_construction_targets**: скрипт, строки 237–244
- **ai_weight**: скрипт, строки 246–248
