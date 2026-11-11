---
type: concept
description: "Вид компании ««Ursus»» — ваниль 1.15, `company_ursus`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Ursus»", "Ursus", "company_ursus"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ursus
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Ursus»

Вид компании · `company_ursus` · `common/company_types/00_companies_europe.txt:946`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/polish_ursus.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_GREATER_POLAND`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 963–965
- **attainable**: скрипт, строки 967–973
- **possible**: скрипт, строки 975–983
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-wheat-farm-throughput-add|building_wheat_farm_throughput_add]] = `0.2` → [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
  - [[vanilla/движок/Модификаторы B#^m-building-rye-farm-throughput-add|building_rye_farm_throughput_add]] = `0.2` → [[vanilla/Здания/Ржаные поля|Ржаные поля]]
- **ai_will_do**: скрипт, строки 990–996
- **ai_construction_targets**: скрипт, строки 998–1005
- **ai_weight**: скрипт, строки 1007–1009
