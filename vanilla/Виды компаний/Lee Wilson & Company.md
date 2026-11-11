---
type: concept
description: "Вид компании «Lee Wilson & Company» — ваниль 1.15, `company_lee_wilson`"
project: vic3
audience: agent
source: vanilla
aliases: ["Lee Wilson & Company", "company_lee_wilson"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lee_wilson
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Lee Wilson & Company

Вид компании · `company_lee_wilson` · `common/company_types/00_companies_mp1.txt:542`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_lee_wilson.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ARKANSAS`
- **building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: `prestige_good_sea_island_cotton`
- **potential**: скрипт, строки 564–567
- **attainable**: скрипт, строки 569–577
- **possible**: скрипт, строки 579–591
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Электростанции|Электростанции]]
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **ai_will_do**: скрипт, строки 598–603
- **ai_construction_targets**: скрипт, строки 605–618
- **ai_weight**: скрипт, строки 620–622
