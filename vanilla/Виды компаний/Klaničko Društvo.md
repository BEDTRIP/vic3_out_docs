---
type: concept
description: "Вид компании «Klaničko Društvo» — ваниль 1.13, `company_klanicko_drustvo`"
project: vic3
source: vanilla
aliases: ["Klaničko Društvo", "company_klanicko_drustvo"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_klanicko_drustvo
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Klaničko Društvo

Вид компании · `company_klanicko_drustvo` · `common/company_types/00_companies_ip3.txt:223`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_klanicko_drustvo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **extension_building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_acorn_fed_pork`
- **potential**: скрипт, строки 243–246
- **attainable**: скрипт, строки 248–256
- **possible**: скрипт, строки 258–270
- **prosperity_modifier**:
  - `building_livestock_ranch_throughput_add` = `0.1` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
  - `building_synthetics_plant_throughput_add` = `0.05` → [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 277–282
- **ai_construction_targets**: скрипт, строки 284–297
- **ai_weight**: скрипт, строки 299–301
