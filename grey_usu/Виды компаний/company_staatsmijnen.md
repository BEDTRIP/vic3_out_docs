---
type: concept
description: "Вид компании «company_staatsmijnen» — grey USU 1.13, `company_staatsmijnen`"
project: vic3
audience: agent
source: grey_usu
aliases: ["company_staatsmijnen"]
tags: [grey_usu, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_staatsmijnen
paths: [grey_add_alot_of_things/grey_usu/common/company_types/zMoG_USU_MUC_rail_company_updates.txt]
---
# company_staatsmijnen

Вид компании · `company_staatsmijnen` · `common/company_types/zMoG_USU_MUC_rail_company_updates.txt:2585`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/staatsmijnen.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`, `STATE_GELRE`
- **possible_prestige_goods**: пусто
- **building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[grey_usu/Здания/Железная дорога|Железная дорога]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 2606–2608
- **attainable**: скрипт, строки 2610–2616
- **possible**: скрипт, строки 2618–2628
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-coal-mine-throughput-add|building_coal_mine_throughput_add]] = `0.1` → [[vanilla/Здания/Угольные шахты|Угольные шахты]]
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.02`
- **ai_will_do**: скрипт, строки 2636–2642
- **ai_construction_targets**: скрипт, строки 2644–2651
- **ai_weight**: скрипт, строки 2652–2654
