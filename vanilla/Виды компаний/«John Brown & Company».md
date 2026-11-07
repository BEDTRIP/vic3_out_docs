---
type: concept
description: "Вид компании ««John Brown & Company»» — ваниль 1.13, `company_john_brown`"
project: vic3
source: vanilla
aliases: ["«John Brown & Company»", "John Brown & Company", "company_john_brown"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_john_brown
paths: [.vanillaVIC3/common/company_types/00_companies_great_britain.txt]
---
# «John Brown & Company»

Вид компании · `company_john_brown` · `common/company_types/00_companies_great_britain.txt:155`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_jb_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOWLANDS`
- **building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_clyde_built_liners`
- **potential**: скрипт, строки 176–178
- **attainable**: скрипт, строки 180–186
- **possible**: скрипт, строки 188–199
- **prosperity_modifier**:
  - `country_prestige_mult` = `0.05`
  - `country_ship_group_supply_ships_construction_efficiency_add` = `0.1`
- **ai_will_do**: скрипт, строки 206–213
- **ai_construction_targets**: скрипт, строки 215–222
- **ai_weight**: скрипт, строки 224–226
