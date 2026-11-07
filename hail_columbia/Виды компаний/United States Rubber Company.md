---
type: concept
description: "Вид компании «United States Rubber Company» — Hail Columbia 1.13, `company_usfp_us_rubber`"
project: vic3
source: hail_columbia
aliases: ["United States Rubber Company", "company_usfp_us_rubber"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_us_rubber
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# United States Rubber Company

Вид компании · `company_usfp_us_rubber` · `common/company_types/usfp_companies.txt:972`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_us_rubber.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CONNECTICUT`
- **building_types**: [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Заводы удобрений|Заводы удобрений]], [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]], [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **potential**: скрипт, строки 992–994
- **possible**: скрипт, строки 996–1004
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.15` → [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.10`
- **ai_will_do**: скрипт, строки 1011–1018
- **ai_construction_targets**: скрипт, строки 1020–1024
- **ai_weight**: скрипт, строки 1026–1028
