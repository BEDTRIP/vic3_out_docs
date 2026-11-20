---
type: explanation
description: "Вид компании ««Ferrocarril Central Córdoba»» — ваниль 1.15.2, `company_cordoba_railway`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Ferrocarril Central Córdoba»", "Ferrocarril Central Córdoba", "company_cordoba_railway"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_cordoba_railway
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Ferrocarril Central Córdoba»

Вид компании · `company_cordoba_railway` · `common/company_types/00_companies_cots.txt:690`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/argentina_cordoba_cenral_railway.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LA_PAMPA`
- **building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **potential**: скрипт, строки 707–710
- **attainable**: скрипт, строки 712–718
- **possible**: скрипт, строки 720–736
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-wheat-farm-throughput-add|building_wheat_farm_throughput_add]] = `0.1` → [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
  - [[vanilla/движок/Модификаторы B#^m-building-livestock-ranch-throughput-add|building_livestock_ranch_throughput_add]] = `0.05` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **ai_will_do**: скрипт, строки 743–749
- **ai_construction_targets**: скрипт, строки 751–759
- **ai_weight**: скрипт, строки 761–763
