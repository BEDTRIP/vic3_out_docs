---
type: concept
description: "Вид компании «Klaničko Društvo» — ваниль 1.15, `company_klanicko_drustvo`"
project: vic3
audience: agent
source: vanilla
aliases: ["Klaničko Društvo", "company_klanicko_drustvo"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_klanicko_drustvo
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Klaničko Društvo

Вид компании · `company_klanicko_drustvo` · `common/company_types/00_companies_ip3.txt:237`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_klanicko_drustvo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **extension_building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_acorn_fed_pork`
- **potential**: скрипт, строки 257–260
- **attainable**: скрипт, строки 262–270
- **possible**: скрипт, строки 272–284
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-livestock-ranch-throughput-add|building_livestock_ranch_throughput_add]] = `0.1` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 291–296
- **ai_construction_targets**: скрипт, строки 298–311
- **ai_weight**: скрипт, строки 313–315
