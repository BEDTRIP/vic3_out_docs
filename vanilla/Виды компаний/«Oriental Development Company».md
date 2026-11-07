---
type: concept
description: "Вид компании ««Oriental Development Company»» — ваниль 1.13, `company_oriental_development_company`"
project: vic3
source: vanilla
aliases: ["«Oriental Development Company»", "Oriental Development Company", "company_oriental_development_company"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_oriental_development_company
paths: [.vanillaVIC3/common/company_types/00_companies_soi.txt]
---
# «Oriental Development Company»

Вид компании · `company_oriental_development_company` · `common/company_types/00_companies_soi.txt:1107`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/oriental_development_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SEOUL`
- **building_types**: [[vanilla/Здания/Рисовые поля|Рисовые поля]], [[vanilla/Здания/Просяные поля|Просяные поля]], [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
- **extension_building_types**: [[vanilla/Здания/Маисовые поля|Маисовые поля]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **possible_prestige_goods**: `prestige_good_generic_grain`
- **prestige_goods_trigger**: скрипт, строки 1130–1135
- **potential**: скрипт, строки 1137–1139
- **attainable**: скрипт, строки 1141–1149
- **possible**: скрипт, строки 1151–1168
- **prosperity_modifier**:
  - `building_railway_throughput_add` = `0.05` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - `state_migration_pull_mult` = `0.1`
- **ai_will_do**: скрипт, строки 1175–1183
- **ai_construction_targets**: скрипт, строки 1185–1213
- **ai_weight**: скрипт, строки 1215–1228
