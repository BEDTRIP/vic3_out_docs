---
type: concept
description: "Вид компании ««Da Afghan Nassaji Sherkat»» — ваниль 1.13, `company_da_afghan_nassaji_sherkat`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Da Afghan Nassaji Sherkat»", "Da Afghan Nassaji Sherkat", "company_da_afghan_nassaji_sherkat"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_da_afghan_nassaji_sherkat
paths: [.vanillaVIC3/common/company_types/00_companies_soi.txt]
---
# «Da Afghan Nassaji Sherkat»

Вид компании · `company_da_afghan_nassaji_sherkat` · `common/company_types/00_companies_soi.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/da_afghan_nassaji_sherkat.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BALKH`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 22–27
- **potential**: скрипт, строки 29–32
- **attainable**: скрипт, строки 34–40
- **possible**: скрипт, строки 42–51
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-mult|state_trade_capacity_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-cotton-plantation-throughput-add|building_cotton_plantation_throughput_add]] = `0.1` → [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **ai_will_do**: скрипт, строки 58–63
- **ai_construction_targets**: скрипт, строки 65–72
- **ai_weight**: скрипт, строки 74–76
