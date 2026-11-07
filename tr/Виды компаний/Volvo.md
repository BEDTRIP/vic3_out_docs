---
type: concept
description: "Вид компании «Volvo» — T&R 1.13, `company_volvo`"
project: vic3
audience: agent
source: tr
aliases: ["Volvo", "company_volvo"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_volvo
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Volvo

Вид компании · `company_volvo` · `common/company_types/ztr_automotive_companies.txt:1047`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swedish_volvo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 1061–1063
- **attainable**: скрипт, строки 1064–1070
- **possible**: скрипт, строки 1071–1081
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-throughput-add|building_group_bg_heavy_industry_throughput_add]] = `0.01`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-light-industry-throughput-add|building_group_bg_light_industry_throughput_add]] = `0.01`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.1`
- **ai_will_do**: скрипт, строки 1087–1093
- **ai_construction_targets**: скрипт, строки 1094–1101
- **ai_weight**: скрипт, строки 1102–1104
