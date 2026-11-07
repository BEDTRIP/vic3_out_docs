---
type: concept
description: "Вид компании «A. Markwald & Company, Ltd» — ваниль 1.13, `company_a_markwald_and_company`"
project: vic3
source: vanilla
aliases: ["A. Markwald & Company, Ltd", "company_a_markwald_and_company"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_a_markwald_and_company
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# A. Markwald & Company, Ltd

Вид компании · `company_a_markwald_and_company` · `common/company_types/00_companies_ep2.txt:1018`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_a_markwald_and_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rice.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BANGKOK`
- **building_types**: [[vanilla/Здания/Рисовые поля|Рисовые поля]], [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_grain`
- **prestige_goods_trigger**: скрипт, строки 1040–1045
- **potential**: скрипт, строки 1047–1049
- **attainable**: скрипт, строки 1051–1059
- **possible**: скрипт, строки 1061–1071
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-logging-throughput-add|building_group_bg_logging_throughput_add]] = `0.1`
- **ai_will_do**: скрипт, строки 1078–1082
- **ai_construction_targets**: скрипт, строки 1084–1091
- **ai_weight**: скрипт, строки 1093–1095
