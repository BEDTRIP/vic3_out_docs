---
type: concept
description: "Вид компании «Sumitomo» — ваниль 1.15, `company_sumitomo`"
project: vic3
audience: agent
source: vanilla
aliases: ["Sumitomo", "company_sumitomo"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sumitomo
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Sumitomo

Вид компании · `company_sumitomo` · `common/company_types/00_companies_ep2.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_sumitomo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANSAI`
- **building_types**: [[vanilla/Здания/Медные рудники|Медные рудники]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 26–31
- **potential**: скрипт, строки 33–35
- **attainable**: скрипт, строки 37–45
- **possible**: скрипт, строки 47–62
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.05` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
- **ai_will_do**: скрипт, строки 69–74
- **ai_construction_targets**: скрипт, строки 76–95
- **ai_weight**: скрипт, строки 97–99
