---
type: explanation
description: "Вид компании «Jakub Klein a spol» — ваниль 1.15.2, `company_jakub_klein`"
project: vic3
audience: agent
source: vanilla
aliases: ["Jakub Klein a spol", "company_jakub_klein"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_jakub_klein
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Jakub Klein a spol

Вид компании · `company_jakub_klein` · `common/company_types/00_companies_ip3.txt:323`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_jakub_klein.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **potential**: скрипт, строки 338–340
- **attainable**: скрипт, строки 342–350
- **possible**: скрипт, строки 352–364
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-paper-mill-throughput-add|building_paper_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.05`
- **ai_will_do**: скрипт, строки 371–376
- **ai_construction_targets**: скрипт, строки 378–391
- **ai_weight**: скрипт, строки 393–395
