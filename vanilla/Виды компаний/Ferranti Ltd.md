---
type: concept
description: "Вид компании «Ferranti Ltd» — ваниль 1.13, `company_ferranti_ltd`"
project: vic3
audience: agent
source: vanilla
aliases: ["Ferranti Ltd", "company_ferranti_ltd"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ferranti_ltd
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Ferranti Ltd

Вид компании · `company_ferranti_ltd` · `common/company_types/00_companies_ep2.txt:787`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_ferranti_ltd.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LANCASHIRE`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]], [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **possible_prestige_goods**: `prestige_good_ferranti_radios`
- **potential**: скрипт, строки 809–812
- **attainable**: скрипт, строки 814–822
- **possible**: скрипт, строки 824–834
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **ai_will_do**: скрипт, строки 841–845
- **ai_construction_targets**: скрипт, строки 847–854
- **ai_weight**: скрипт, строки 856–858
