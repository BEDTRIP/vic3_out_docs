---
type: concept
description: "Вид компании «Beiersdorf» — T&R 1.13, `company_beiersdorf`"
project: vic3
audience: agent
source: tr
aliases: ["Beiersdorf", "company_beiersdorf"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_beiersdorf
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_cosmetics_companies.txt]
---
# Beiersdorf

Вид компании · `company_beiersdorf` · `common/company_types/ztr_cosmetics_companies.txt:300`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_beiersdorf.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ELBE`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]], [[tr/Здания/Заводы синтетики|Заводы синтетики]]
- **potential**: скрипт, строки 314–316
- **possible_prestige_goods**: `prestige_good_hygiene_cosmetics`
- **attainable**: скрипт, строки 320–327
- **possible**: скрипт, строки 328–338
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-chemical-plant-throughput-add|building_chemical_plant_throughput_add]] = `0.1` → [[tr/Здания/Заводы удобрений|Заводы удобрений]]
  - [[vanilla/движок/Модификаторы C#^m-country-institution-cost-institution-health-system-mult|country_institution_cost_institution_health_system_mult]] = `-0.1`
- **ai_will_do**: скрипт, строки 343–349
- **ai_construction_targets**: скрипт, строки 350–357
- **ai_weight**: скрипт, строки 358–360
