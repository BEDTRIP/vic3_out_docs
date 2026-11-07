---
type: concept
description: "Вид компании «Colt's Patent Firearms Manufacturing Company» — ваниль 1.13, `company_colt_firearms`"
project: vic3
source: vanilla
aliases: ["Colt's Patent Firearms Manufacturing Company", "company_colt_firearms"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_colt_firearms
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Colt's Patent Firearms Manufacturing Company

Вид компании · `company_colt_firearms` · `common/company_types/00_companies_mp1.txt:628`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_colt_firearms.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CONNECTICUT`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **possible_prestige_goods**: `prestige_good_colt_revolvers`
- **potential**: скрипт, строки 648–651
- **attainable**: скрипт, строки 653–661
- **possible**: скрипт, строки 663–672
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-arms-industry-throughput-add|building_arms_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Оружейные заводы|Оружейные заводы]]
  - [[vanilla/движок/Модификаторы U#^m-unit-army-offense-mult|unit_army_offense_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 679–684
- **ai_construction_targets**: скрипт, строки 686–693
- **ai_weight**: скрипт, строки 695–697
