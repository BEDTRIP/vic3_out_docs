---
type: concept
description: "Вид компании «Shein» — T&R 1.13, `company_shein`"
project: vic3
source: tr
aliases: ["Shein", "company_shein"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_shein
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_ecommerce_companies.txt]
---
# Shein

Вид компании · `company_shein` · `common/company_types/ztr_ecommerce_companies.txt:8`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_shein.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_e_commerce.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SUZHOU`
- **building_types**: [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/E-Commerce Logistic Centers|E-Commerce Logistic Centers]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]], [[tr/Здания/Заводы синтетики|Заводы синтетики]], [[tr/Здания/Каучуковые плантации|Каучуковые плантации]]
- **potential**: скрипт, строки 31–33
- **attainable**: скрипт, строки 35–41
- **possible**: скрипт, строки 43–53
- **prosperity_modifier**:
  - `building_mendelejew_synthetic_rubber_factory_throughput_add` = `0.05` → [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
  - `building_textile_mill_throughput_add` = `0.05` → [[tr/Здания/Текстильные фабрики|Текстильные фабрики]]
  - `building_datacenter_industry_throughput_add` = `0.05` → [[tr/Здания/Datacenters|Datacenters]]
- **ai_will_do**: скрипт, строки 61–67
- **ai_construction_targets**: скрипт, строки 69–76
- **ai_weight**: скрипт, строки 78–80
