---
type: concept
description: "Вид компании «Bosch» — T&R 1.13, `company_bosch`"
project: vic3
source: tr
aliases: ["Bosch", "company_bosch"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bosch
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_furniture_companies.txt]
---
# Bosch

Вид компании · `company_bosch` · `common/company_types/ztr_furniture_companies.txt:199`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_bosch.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WURTTEMBERG`, `STATE_BAVARIA`
- **building_types**: [[tr/Здания/Производства инструментов|Производства инструментов]], [[tr/Здания/Robotics Industries|Robotics Industries]]
- **extension_building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]], [[tr/Здания/Моторные заводы|Моторные заводы]]
- **potential**: скрипт, строки 216–218
- **attainable**: скрипт, строки 219–226
- **possible**: скрипт, строки 227–237
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.33` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **ai_will_do**: скрипт, строки 241–247
- **ai_construction_targets**: скрипт, строки 248–255
- **ai_weight**: скрипт, строки 256–258
