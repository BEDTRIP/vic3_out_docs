---
type: concept
description: "Вид компании ««Sunhwaguk»» — ваниль 1.15, `company_sunhwaguk`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Sunhwaguk»", "Sunhwaguk", "company_sunhwaguk"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sunhwaguk
paths: [.vanillaVIC3/common/company_types/00_companies_asia.txt]
---
# «Sunhwaguk»

Вид компании · `company_sunhwaguk` · `common/company_types/00_companies_asia.txt:551`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/korea_sunhwaguk.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Табачные плантации|Табачные плантации]], [[vanilla/Здания/Рисовые поля|Рисовые поля]]
- **extension_building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_generic_grain`
- **prestige_goods_trigger**: скрипт, строки 571–576
- **potential**: скрипт, строки 578–580
- **attainable**: скрипт, строки 582–588
- **possible**: скрипт, строки 590–602
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-tech-spread-mult|country_tech_spread_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 608–615
- **ai_construction_targets**: скрипт, строки 617–627
- **ai_weight**: скрипт, строки 629–631
