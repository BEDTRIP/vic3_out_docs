---
type: concept
description: "Вид компании ««Nokia»» — ваниль 1.13, `company_nokia`"
project: vic3
source: vanilla
aliases: ["«Nokia»", "Nokia", "company_nokia"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nokia
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Nokia»

Вид компании · `company_nokia` · `common/company_types/00_companies_europe.txt:870`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/finland_nokia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_UUSIMAA`
- **building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_generic_paper`
- **prestige_goods_trigger**: скрипт, строки 892–897
- **potential**: скрипт, строки 899–901
- **attainable**: скрипт, строки 903–909
- **possible**: скрипт, строки 911–921
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Электрозаводы|Электрозаводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 928–934
- **ai_construction_targets**: скрипт, строки 936–943
- **ai_weight**: скрипт, строки 945–947
