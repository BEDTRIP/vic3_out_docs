---
type: concept
description: "Вид компании ««Bongah-e Enhesar-e Saderat-e Taryak»» — ваниль 1.15, `company_opium_export_monopoly`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Bongah-e Enhesar-e Saderat-e Taryak»", "Bongah-e Enhesar-e Saderat-e Taryak", "company_opium_export_monopoly"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_opium_export_monopoly
paths: [.vanillaVIC3/common/company_types/00_companies_soi.txt]
---
# «Bongah-e Enhesar-e Saderat-e Taryak»

Вид компании · `company_opium_export_monopoly` · `common/company_types/00_companies_soi.txt:370`

## Поля

- **icon**: `gfx/interface/icons/company_icons/basic_colonial_plantations_1.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ISFAHAN`
- **building_types**: [[vanilla/Здания/Маковые плантации|Маковые плантации]]
- **extension_building_types**: [[vanilla/Здания/Табачные плантации|Табачные плантации]]
- **possible_prestige_goods**: `prestige_good_generic_opium`
- **prestige_goods_trigger**: скрипт, строки 392–397
- **potential**: скрипт, строки 399–401
- **attainable**: скрипт, строки 403–411
- **possible**: скрипт, строки 413–423
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 430–435
- **ai_construction_targets**: скрипт, строки 437–445
- **ai_weight**: скрипт, строки 447–449
