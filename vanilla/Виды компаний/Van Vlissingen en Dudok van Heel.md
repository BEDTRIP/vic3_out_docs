---
type: concept
description: "Вид компании «Van Vlissingen en Dudok van Heel» — ваниль 1.15, `company_van_vlissingen_en_dudok_van_heel`"
project: vic3
audience: agent
source: vanilla
aliases: ["Van Vlissingen en Dudok van Heel", "company_van_vlissingen_en_dudok_van_heel"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_van_vlissingen_en_dudok_van_heel
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Van Vlissingen en Dudok van Heel

Вид компании · `company_van_vlissingen_en_dudok_van_heel` · `common/company_types/00_companies_ep2.txt:862`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_van_vlissingen_en_dudok_van_heel.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Верфи|Верфи]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 888–891
- **attainable**: скрипт, строки 893–901
- **possible**: скрипт, строки 903–913
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-sugar-plantation-throughput-add|building_sugar_plantation_throughput_add]] = `0.1` → [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]]
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.05` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-mult|state_infrastructure_from_population_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 921–925
- **ai_construction_targets**: скрипт, строки 927–934
- **ai_weight**: скрипт, строки 936–938
