---
type: concept
description: "Вид компании «Ferrari» — T&R 1.13, `company_ferrari`"
project: vic3
source: tr
aliases: ["Ferrari", "company_ferrari"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ferrari
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Ferrari

Вид компании · `company_ferrari` · `common/company_types/ztr_automotive_companies.txt:619`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/italian_ferrari.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EMILIA`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 633–635
- **attainable**: скрипт, строки 636–642
- **possible**: скрипт, строки 643–653
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.05`
  - `building_elgar_opera_throughput_add` = `0.05` → [[tr/Здания/Entertainment Areas|Entertainment Areas]]
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.05` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 660–666
- **ai_construction_targets**: скрипт, строки 667–674
- **ai_weight**: скрипт, строки 675–677
