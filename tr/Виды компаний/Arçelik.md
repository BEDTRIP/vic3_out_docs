---
type: concept
description: "Вид компании «Arçelik» — T&R 1.13, `company_arcelik`"
project: vic3
source: tr
aliases: ["Arçelik", "company_arcelik"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_arcelik
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_furniture_companies.txt]
---
# Arçelik

Вид компании · `company_arcelik` · `common/company_types/ztr_furniture_companies.txt:379`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/turkish_arcelik.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]]
- **extension_building_types**: [[tr/Здания/Мебельные фабрики|Мебельные фабрики]]
- **potential**: скрипт, строки 392–394
- **attainable**: скрипт, строки 395–402
- **possible**: скрипт, строки 403–413
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[tr/Здания/Текстильные фабрики|Текстильные фабрики]]
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.25`
- **ai_will_do**: скрипт, строки 418–424
- **ai_construction_targets**: скрипт, строки 425–432
- **ai_weight**: скрипт, строки 433–435
