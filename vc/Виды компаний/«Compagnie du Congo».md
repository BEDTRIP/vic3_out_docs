---
type: concept
description: "Вид компании ««Compagnie du Congo»» — VC 1.15, `company_ccci`"
project: vic3
audience: agent
source: vc
aliases: ["«Compagnie du Congo»", "Compagnie du Congo", "company_ccci"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ccci
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Compagnie du Congo»]]"
---
# «Compagnie du Congo»

Вид компании · `company_ccci` · `common/company_types/joi_companies.txt:5521`

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
- **potential**: скрипт, строки 5540–5545
- **possible**: скрипт, строки 5547–5566
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-rubber-employee-mult|building_group_bg_rubber_employee_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-rubber-mult|goods_output_rubber_mult]] = `0.15` → [[vanilla/Товары/Каучук|Каучук]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-rubber-mortality-mult|building_group_bg_rubber_mortality_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 5574–5585
- **ai_construction_targets**: скрипт, строки 5587–5594
- **ai_weight**: скрипт, строки 5596–5598
