---
type: concept
description: "Вид компании «Jakub Klein a spol» — ваниль 1.13, `company_jakub_klein`"
project: vic3
source: vanilla
aliases: ["Jakub Klein a spol", "company_jakub_klein"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_jakub_klein
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Jakub Klein a spol

Вид компании · `company_jakub_klein` · `common/company_types/00_companies_ip3.txt:305`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_jakub_klein.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **potential**: скрипт, строки 320–322
- **attainable**: скрипт, строки 324–332
- **possible**: скрипт, строки 334–346
- **prosperity_modifier**:
  - `building_paper_mill_throughput_add` = `0.1` → [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]]
  - `building_group_bg_agriculture_throughput_add` = `0.05`
- **ai_will_do**: скрипт, строки 353–358
- **ai_construction_targets**: скрипт, строки 360–373
- **ai_weight**: скрипт, строки 375–377
