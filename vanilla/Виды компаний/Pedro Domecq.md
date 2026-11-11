---
type: concept
description: "Вид компании «Pedro Domecq» — ваниль 1.15, `company_pedro_domecq`"
project: vic3
audience: agent
source: vanilla
aliases: ["Pedro Domecq", "company_pedro_domecq"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_pedro_domecq
paths: [.vanillaVIC3/common/company_types/00_companies_ip4.txt]
---
# Pedro Domecq

Вид компании · `company_pedro_domecq` · `common/company_types/00_companies_ip4.txt:645`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_pedro_domecq.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Виноградники|Виноградники]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Рисовые поля|Рисовые поля]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **possible_prestige_goods**: `prestige_good_sherry`
- **potential**: скрипт, строки 667–670
- **attainable**: скрипт, строки 672–678
- **possible**: скрипт, строки 680–686
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 693–697
- **ai_construction_targets**: скрипт, строки 699–706
- **ai_weight**: скрипт, строки 708–710
