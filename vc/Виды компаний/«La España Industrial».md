---
type: concept
description: "Вид компании ««La España Industrial»» — VC 1.13, `company_espana_industrial`"
project: vic3
audience: agent
source: vc
aliases: ["«La España Industrial»", "La España Industrial", "company_espana_industrial"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_espana_industrial
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«La España Industrial»]]"
---
# «La España Industrial»

Вид компании · `company_espana_industrial` · `common/company_types/joi_companies.txt:6802`

## Отличия от ваниль

- **potential**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/spain_la_espana_industrial.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CATALONIA`
- **building_types**: [[vc/Здания/Текстильные фабрики|Текстильные фабрики]], [[vc/Здания/Плантации хлопка|Плантации хлопка]]
- **extension_building_types**: [[vc/Здания/Плантации шёлка|Плантации шёлка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 6823–6828
- **potential**: скрипт, строки 6830–6833
- **attainable**: скрипт, строки 6835–6841
- **possible**: скрипт, строки 6843–6853
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `0.2`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-employee-mult|building_group_bg_mining_employee_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 6861–6867
- **ai_construction_targets**: скрипт, строки 6869–6876
- **ai_weight**: скрипт, строки 6878–6880
