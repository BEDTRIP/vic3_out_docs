---
type: concept
description: "Вид компании ««Ursus»» — ваниль 1.13, `company_ursus`"
project: vic3
source: vanilla
aliases: ["«Ursus»", "Ursus", "company_ursus"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ursus
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Ursus»

Вид компании · `company_ursus` · `common/company_types/00_companies_europe.txt:951`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/polish_ursus.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_GREATER_POLAND`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 968–970
- **attainable**: скрипт, строки 972–978
- **possible**: скрипт, строки 980–990
- **prosperity_modifier**:
  - `building_wheat_farm_throughput_add` = `0.2` → [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
  - `building_rye_farm_throughput_add` = `0.2` → [[vanilla/Здания/Ржаные поля|Ржаные поля]]
- **ai_will_do**: скрипт, строки 997–1003
- **ai_construction_targets**: скрипт, строки 1005–1012
- **ai_weight**: скрипт, строки 1014–1016
