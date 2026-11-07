---
type: concept
description: "Вид компании «Erste Brünner Maschinenfabriks-Gesellschaft» — ваниль 1.13, `company_erste_brunner`"
project: vic3
audience: agent
source: vanilla
aliases: ["Erste Brünner Maschinenfabriks-Gesellschaft", "company_erste_brunner"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_erste_brunner
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Erste Brünner Maschinenfabriks-Gesellschaft

Вид компании · `company_erste_brunner` · `common/company_types/00_companies_ip3.txt:701`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_erste_brunner.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: `prestige_good_brunn_type_engines`
- **potential**: скрипт, строки 720–723
- **attainable**: скрипт, строки 725–733
- **possible**: скрипт, строки 735–747
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.1` → [[vanilla/Здания/Электростанции|Электростанции]]
- **ai_will_do**: скрипт, строки 754–759
- **ai_construction_targets**: скрипт, строки 761–774
- **ai_weight**: скрипт, строки 776–778
