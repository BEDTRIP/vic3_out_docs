---
type: concept
description: "Вид компании ««Chemins de fer Orientaux»» — grey USU 1.13, `company_orient_express`"
project: vic3
audience: agent
source: grey_usu
aliases: ["«Chemins de fer Orientaux»", "Chemins de fer Orientaux", "company_orient_express"]
tags: [grey_usu, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_orient_express
paths: [grey_add_alot_of_things/grey_usu/common/company_types/yMoG_USU_companies_rail_overwrite.txt]
replaces: "[[vanilla/Виды компаний/«Chemins de fer Orientaux»]]"
---
# «Chemins de fer Orientaux»

Вид компании · `company_orient_express` · `common/company_types/yMoG_USU_companies_rail_overwrite.txt:377`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **ai_construction_targets**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chemins_de_fer_orientaux.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **building_types**: [[grey_usu/Здания/Железнодорожный терминал|Железнодорожный терминал]], [[grey_usu/Здания/Железная дорога|Железная дорога]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[grey_usu/Здания/Речные доки|Речные доки]]
- **potential**: скрипт, строки 398–403
- **attainable**:
  - `owns_entire_state_region` = `STATE_EASTERN_THRACE`
- **possible**: скрипт, строки 409–423
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 429–438
- **ai_construction_targets**: скрипт, строки 440–448
- **ai_weight**: скрипт, строки 450–452
