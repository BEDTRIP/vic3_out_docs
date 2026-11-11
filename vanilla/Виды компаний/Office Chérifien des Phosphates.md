---
type: concept
description: "Вид компании «Office Chérifien des Phosphates» — ваниль 1.15, `company_office_cherifien_des_phosphates`"
project: vic3
audience: agent
source: vanilla
aliases: ["Office Chérifien des Phosphates", "company_office_cherifien_des_phosphates"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_office_cherifien_des_phosphates
paths: [.vanillaVIC3/common/company_types/00_companies_ip4.txt]
---
# Office Chérifien des Phosphates

Вид компании · `company_office_cherifien_des_phosphates` · `common/company_types/00_companies_ip4.txt:457`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_office_cherifien_des_phosphates.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: `prestige_good_generic_fertilizer`
- **prestige_goods_trigger**: скрипт, строки 478–483
- **potential**: скрипт, строки 485–487
- **attainable**: скрипт, строки 489–495
- **possible**: скрипт, строки 497–503
- **ai_will_do**: скрипт, строки 505–510
- **ai_construction_targets**: скрипт, строки 512–519
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-sulfur-mine-throughput-add|building_sulfur_mine_throughput_add]] = `0.05` → [[vanilla/Здания/Серные рудники|Серные рудники]]
- **ai_weight**: скрипт, строки 526–528
