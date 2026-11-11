---
type: concept
description: "Вид компании ««Manufacture d'armes de Saint-Étienne»» — ваниль 1.15, `company_saint_etienne`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Manufacture d'armes de Saint-Étienne»", "Manufacture d'armes de Saint-Étienne", "company_saint_etienne"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_saint_etienne
paths: [.vanillaVIC3/common/company_types/00_companies_france.txt]
---
# «Manufacture d'armes de Saint-Étienne»

Вид компании · `company_saint_etienne` · `common/company_types/00_companies_france.txt:297`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_saint_etienne.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RHONE`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **possible_prestige_goods**: `prestige_good_saint_etienne_rifles`
- **potential**: скрипт, строки 319–321
- **attainable**: скрипт, строки 323–329
- **possible**: скрипт, строки 331–339
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 346–352
- **ai_construction_targets**: скрипт, строки 354–361
- **ai_weight**: скрипт, строки 363–371
