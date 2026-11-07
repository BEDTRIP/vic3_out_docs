---
type: concept
description: "Вид компании ««Chemins de fer Orientaux»» — VC 1.13, `company_orient_express`"
project: vic3
audience: agent
source: vc
aliases: ["«Chemins de fer Orientaux»", "Chemins de fer Orientaux", "company_orient_express"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_orient_express
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Chemins de fer Orientaux»]]"
---
# «Chemins de fer Orientaux»

Вид компании · `company_orient_express` · `common/company_types/joi_companies.txt:5443`

## Отличия от ваниль

- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chemins_de_fer_orientaux.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]]
- **potential**: скрипт, строки 5461–5466
- **attainable**:
  - `owns_entire_state_region` = `STATE_EASTERN_THRACE`
- **possible**: скрипт, строки 5472–5485
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-infrastructure-employee-mult|building_group_bg_infrastructure_employee_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-construction-goods-cost-mult|country_construction_goods_cost_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 5494–5502
- **ai_construction_targets**: скрипт, строки 5504–5512
- **ai_weight**: скрипт, строки 5514–5516
