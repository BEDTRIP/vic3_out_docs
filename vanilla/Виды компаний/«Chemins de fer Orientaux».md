---
type: explanation
description: "Вид компании ««Chemins de fer Orientaux»» — ваниль 1.15.2, `company_orient_express`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Chemins de fer Orientaux»", "Chemins de fer Orientaux", "company_orient_express"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_orient_express
paths: [.vanillaVIC3/common/company_types/00_companies_asia.txt]
---
# «Chemins de fer Orientaux»

Вид компании · `company_orient_express` · `common/company_types/00_companies_asia.txt:322`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chemins_de_fer_orientaux.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **potential**: скрипт, строки 340–345
- **attainable**:
  - `owns_entire_state_region` = `STATE_EASTERN_THRACE`
- **possible**: скрипт, строки 351–365
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 371–380
- **ai_construction_targets**: скрипт, строки 382–390
- **ai_weight**: скрипт, строки 392–394
