---
type: concept
description: "Вид компании «Maison Worth» — ваниль 1.13, `company_maison_worth`"
project: vic3
source: vanilla
aliases: ["Maison Worth", "company_maison_worth"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_maison_worth
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Maison Worth

Вид компании · `company_maison_worth` · `common/company_types/00_companies_mp1.txt:466`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_maison_worth.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **category**: `shopkeeper_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]], [[vanilla/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_haute_couture`
- **potential**: скрипт, строки 489–492
- **attainable**: скрипт, строки 494–502
- **possible**: скрипт, строки 504–513
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 521–526
- **ai_construction_targets**: скрипт, строки 528–535
- **ai_weight**: скрипт, строки 537–539
