---
type: concept
description: "Вид компании ««Fundição Ipanema»» — ваниль 1.13, `company_fundicao_ipanema`"
project: vic3
source: vanilla
aliases: ["«Fundição Ipanema»", "Fundição Ipanema", "company_fundicao_ipanema"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fundicao_ipanema
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Fundição Ipanema»

Вид компании · `company_fundicao_ipanema` · `common/company_types/00_companies_cots.txt:245`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_fundicao_ipanema.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SAO_PAULO`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 266–271
- **potential**: скрипт, строки 273–276
- **attainable**: скрипт, строки 278–284
- **possible**: скрипт, строки 286–295
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-munition-plant-throughput-add|building_munition_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
  - [[vanilla/движок/Модификаторы B#^m-building-arms-industry-throughput-add|building_arms_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Оружейные заводы|Оружейные заводы]]
- **ai_will_do**: скрипт, строки 302–307
- **ai_construction_targets**: скрипт, строки 309–322
- **ai_weight**: скрипт, строки 324–326
