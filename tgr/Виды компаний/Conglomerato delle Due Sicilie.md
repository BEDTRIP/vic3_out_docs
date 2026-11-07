---
type: concept
description: "Вид компании «Conglomerato delle Due Sicilie» — TGR 1.13, `company_mantero_seta_two_sicilies`"
project: vic3
source: tgr
aliases: ["Conglomerato delle Due Sicilie", "company_mantero_seta_two_sicilies"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mantero_seta_two_sicilies
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
---
# Conglomerato delle Due Sicilie

Вид компании · `company_mantero_seta_two_sicilies` · `common/company_types/TGR_TRADE_companies.txt:738`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_anglo_sicilian_sulphur_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CAMPANIA`
- **building_types**: [[vanilla/Здания/Виноградники|Виноградники]], [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]], [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_champagne`
- **potential**: пусто
- **attainable**: пусто
- **possible**: скрипт, строки 769–780
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.1` → [[tgr/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 787–792
- **ai_construction_targets**: скрипт, строки 794–801
- **ai_weight**: скрипт, строки 803–805
