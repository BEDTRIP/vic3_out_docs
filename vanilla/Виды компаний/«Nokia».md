---
type: concept
description: "Вид компании ««Nokia»» — ваниль 1.15, `company_nokia`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Nokia»", "Nokia", "company_nokia"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nokia
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Nokia»

Вид компании · `company_nokia` · `common/company_types/00_companies_europe.txt:867`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/finland_nokia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_UUSIMAA`
- **building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_generic_paper`
- **prestige_goods_trigger**: скрипт, строки 889–894
- **potential**: скрипт, строки 896–898
- **attainable**: скрипт, строки 900–906
- **possible**: скрипт, строки 908–916
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Электрозаводы|Электрозаводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 923–929
- **ai_construction_targets**: скрипт, строки 931–938
- **ai_weight**: скрипт, строки 940–942
