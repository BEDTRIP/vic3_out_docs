---
type: concept
description: "Вид компании «Lee Wilson & Company» — ваниль 1.13, `company_lee_wilson`"
project: vic3
source: vanilla
aliases: ["Lee Wilson & Company", "company_lee_wilson"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lee_wilson
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Lee Wilson & Company

Вид компании · `company_lee_wilson` · `common/company_types/00_companies_mp1.txt:544`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_lee_wilson.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ARKANSAS`
- **building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: `prestige_good_sea_island_cotton`
- **potential**: скрипт, строки 566–569
- **attainable**: скрипт, строки 571–579
- **possible**: скрипт, строки 581–593
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Электростанции|Электростанции]]
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **ai_will_do**: скрипт, строки 600–605
- **ai_construction_targets**: скрипт, строки 607–620
- **ai_weight**: скрипт, строки 622–624
