---
type: concept
description: "Вид компании «Honda» — T&R 1.13, `company_honda`"
project: vic3
audience: agent
source: tr
aliases: ["Honda", "company_honda"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_honda
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Honda

Вид компании · `company_honda` · `common/company_types/ztr_automotive_companies.txt:226`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_honda.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Robotics Industries|Robotics Industries]]
- **possible_prestige_goods**: `prestige_good_asia_automobiles`
- **prestige_goods_trigger**: скрипт, строки 243–248
- **potential**: скрипт, строки 249–251
- **attainable**: скрипт, строки 252–258
- **possible**: скрипт, строки 259–269
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.05` → [[tr/Здания/верфи|верфи]]
  - `building_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **ai_will_do**: скрипт, строки 274–280
- **ai_construction_targets**: скрипт, строки 281–288
- **ai_weight**: скрипт, строки 289–291
