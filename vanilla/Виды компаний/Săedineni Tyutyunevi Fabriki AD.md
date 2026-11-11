---
type: concept
description: "Вид компании «Săedineni Tyutyunevi Fabriki AD» — ваниль 1.15, `company_united_tobacco_factories`"
project: vic3
audience: agent
source: vanilla
aliases: ["Săedineni Tyutyunevi Fabriki AD", "company_united_tobacco_factories"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_united_tobacco_factories
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Săedineni Tyutyunevi Fabriki AD

Вид компании · `company_united_tobacco_factories` · `common/company_types/00_companies_ip3.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_united_tobacco_factories.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Табачные плантации|Табачные плантации]]
- **extension_building_types**: [[vanilla/Здания/Маковые плантации|Маковые плантации]]
- **possible_prestige_goods**: `prestige_good_basma_tobacco`
- **potential**: скрипт, строки 22–25
- **attainable**: пусто
- **possible**: скрипт, строки 30–43
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-trade-center-throughput-add|building_trade_center_throughput_add]] = `0.05` → [[vanilla/Здания/Торговые центры|Торговые центры]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pop-attraction-mult|interest_group_ig_industrialists_pop_attraction_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-approval-add|interest_group_ig_industrialists_approval_add]] = `3`
- **ai_will_do**: скрипт, строки 51–58
- **ai_construction_targets**: скрипт, строки 60–70
- **ai_weight**: скрипт, строки 72–74
