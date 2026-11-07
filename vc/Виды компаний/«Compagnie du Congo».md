---
type: concept
description: "Вид компании ««Compagnie du Congo»» — VC 1.13, `company_ccci`"
project: vic3
source: vc
aliases: ["«Compagnie du Congo»", "Compagnie du Congo", "company_ccci"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ccci
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Compagnie du Congo»]]"
---
# «Compagnie du Congo»

Вид компании · `company_ccci` · `common/company_types/joi_companies.txt:5519`

## Отличия от ваниль

- **category**: `aristocrat_owned` → `bureaucrat_owned`
- **potential**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ccci.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Каучуковые плантации|Каучуковые плантации]], [[vc/Здания/Лесозаготовки|Лесозаготовки]], [[vc/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vc/Здания/Животноводческие фермы|Животноводческие фермы]]
- **potential**: скрипт, строки 5538–5543
- **possible**: скрипт, строки 5545–5564
- **prosperity_modifier**:
  - `building_group_bg_rubber_employee_mult` = `-0.25`
  - `goods_output_rubber_mult` = `0.15` → [[vanilla/Товары/Каучук|Каучук]]
  - `building_group_bg_rubber_mortality_mult` = `0.1`
- **ai_will_do**: скрипт, строки 5572–5583
- **ai_construction_targets**: скрипт, строки 5585–5592
- **ai_weight**: скрипт, строки 5594–5596
