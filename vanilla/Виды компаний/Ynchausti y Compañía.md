---
type: concept
description: "Вид компании «Ynchausti y Compañía» — ваниль 1.13, `company_ynchausti_y_compania`"
project: vic3
audience: agent
source: vanilla
aliases: ["Ynchausti y Compañía", "company_ynchausti_y_compania"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ynchausti_y_compania
paths: [.vanillaVIC3/common/company_types/00_companies_ip4.txt]
---
# Ynchausti y Compañía

Вид компании · `company_ynchausti_y_compania` · `common/company_types/00_companies_ip4.txt:345`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_ynchausti_y_compania.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Порты|Порты]], [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]]
- **extension_building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Рисовые поля|Рисовые поля]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 366–371
- **potential**: скрипт, строки 373–376
- **attainable**: скрипт, строки 378–387
- **possible**: скрипт, строки 389–405
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 412–420
- **ai_construction_targets**: скрипт, строки 422–451
- **ai_weight**: скрипт, строки 453–455
