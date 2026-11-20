---
type: explanation
description: "Вид компании ««John Brown & Company»» — ваниль 1.15.2, `company_john_brown`"
project: vic3
audience: agent
source: vanilla
aliases: ["«John Brown & Company»", "John Brown & Company", "company_john_brown"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_john_brown
paths: [.vanillaVIC3/common/company_types/00_companies_great_britain.txt]
---
# «John Brown & Company»

Вид компании · `company_john_brown` · `common/company_types/00_companies_great_britain.txt:159`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_jb_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOWLANDS`
- **building_types**: [[vanilla/Здания/Верфи|Верфи]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_clyde_built_liners`
- **potential**: скрипт, строки 180–182
- **attainable**: скрипт, строки 184–190
- **possible**: скрипт, строки 192–205
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.1`
- **ai_will_do**: скрипт, строки 212–219
- **ai_construction_targets**: скрипт, строки 221–228
- **ai_weight**: скрипт, строки 230–232
