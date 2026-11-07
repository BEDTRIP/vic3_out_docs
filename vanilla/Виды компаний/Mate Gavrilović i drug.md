---
type: concept
description: "Вид компании «Mate Gavrilović i drug» — ваниль 1.13, `company_mate_gavrilovic`"
project: vic3
source: vanilla
aliases: ["Mate Gavrilović i drug", "company_mate_gavrilovic"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mate_gavrilovic
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Mate Gavrilović i drug

Вид компании · `company_mate_gavrilovic` · `common/company_types/00_companies_ip3.txt:78`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_mate_gavrilovic.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **category**: `shopkeeper_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **potential**: скрипт, строки 98–100
- **attainable**: скрипт, строки 102–110
- **possible**: скрипт, строки 112–121
- **prosperity_modifier**:
  - `unit_morale_recovery_mult` = `0.1`
  - `building_livestock_ranch_throughput_add` = `0.1` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
  - `interest_group_ig_petty_bourgeoisie_approval_add` = `2`
- **ai_will_do**: скрипт, строки 129–134
- **ai_construction_targets**: скрипт, строки 136–143
- **ai_weight**: скрипт, строки 145–147
