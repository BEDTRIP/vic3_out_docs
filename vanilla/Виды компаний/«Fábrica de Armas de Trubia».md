---
type: concept
description: "Вид компании ««Fábrica de Armas de Trubia»» — ваниль 1.13, `company_trubia`"
project: vic3
source: vanilla
aliases: ["«Fábrica de Armas de Trubia»", "Fábrica de Armas de Trubia", "company_trubia"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_trubia
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Fábrica de Armas de Trubia»

Вид компании · `company_trubia` · `common/company_types/00_companies_europe.txt:1453`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/spain_fabrica_de_armas_de_trubia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ASTURIAS`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **possible_prestige_goods**: `prestige_good_generic_artillery`
- **prestige_goods_trigger**: скрипт, строки 1475–1480
- **potential**: скрипт, строки 1482–1484
- **attainable**: скрипт, строки 1486–1492
- **possible**: скрипт, строки 1494–1504
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-military-goods-cost-mult|country_military_goods_cost_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 1511–1517
- **ai_construction_targets**: скрипт, строки 1519–1526
- **ai_weight**: скрипт, строки 1528–1530
