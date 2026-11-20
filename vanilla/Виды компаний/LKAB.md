---
type: explanation
description: "Вид компании «LKAB» — ваниль 1.15.2, `company_lkab`"
project: vic3
audience: agent
source: vanilla
aliases: ["LKAB", "company_lkab"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lkab
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# LKAB

Вид компании · `company_lkab` · `common/company_types/00_companies_europe.txt:636`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/lkab.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NORRLAND`
- **building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_swedish_bar_iron`
- **potential**: скрипт, строки 658–660
- **attainable**: скрипт, строки 662–668
- **possible**: скрипт, строки 670–681
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-iron-mine-throughput-add|building_iron_mine_throughput_add]] = `0.2` → [[vanilla/Здания/Железные рудники|Железные рудники]]
- **ai_will_do**: скрипт, строки 687–693
- **ai_construction_targets**: скрипт, строки 695–708
- **ai_weight**: скрипт, строки 710–712
