---
type: concept
description: "Вид компании «Levi's» — T&R 1.13, `company_levi_strauss`"
project: vic3
audience: agent
source: tr
aliases: ["Levi's", "company_levi_strauss"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_levi_strauss
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_textile_companies.txt]
---
# Levi's

Вид компании · `company_levi_strauss` · `common/company_types/ztr_textile_companies.txt:353`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_levi_strauss.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_fashion.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tr/Здания/Плантации хлопка|Плантации хлопка]]
- **extension_building_types**: [[tr/Здания/Каучуковые плантации|Каучуковые плантации]]
- **possible_prestige_goods**: `prestige_good_levis_denim`
- **potential**: скрипт, строки 370–372
- **attainable**: скрипт, строки 373–380
- **possible**: скрипт, строки 381–391
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-cotton-plantation-throughput-add|building_cotton_plantation_throughput_add]] = `0.05` → [[tr/Здания/Плантации хлопка|Плантации хлопка]]
  - `building_water_plant_throughput_add` = `0.05` → [[tr/Здания/Water Plants|Water Plants]]
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-cultural-minority-mult|state_pop_support_movement_cultural_minority_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 397–403
- **ai_construction_targets**: скрипт, строки 404–411
- **ai_weight**: скрипт, строки 412–414
