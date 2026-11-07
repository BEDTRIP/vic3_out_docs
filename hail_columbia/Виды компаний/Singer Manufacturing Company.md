---
type: concept
description: "Вид компании «Singer Manufacturing Company» — Hail Columbia 1.13, `company_usfp_singer`"
project: vic3
source: hail_columbia
aliases: ["Singer Manufacturing Company", "company_usfp_singer"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_singer
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# Singer Manufacturing Company

Вид компании · `company_usfp_singer` · `common/company_types/usfp_companies.txt:809`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_singer.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_YORK`, `STATE_NEW_JERSEY`
- **building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_generic_tools`
- **prestige_goods_trigger**: скрипт, строки 830–835
- **potential**: скрипт, строки 837–846
- **possible**: скрипт, строки 848–861
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.15` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-spread-mult|country_production_tech_spread_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 868–880
- **ai_construction_targets**: скрипт, строки 882–892
- **ai_weight**: скрипт, строки 894–896
