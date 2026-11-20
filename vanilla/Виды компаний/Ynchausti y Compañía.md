---
type: explanation
description: "Вид компании «Ynchausti y Compañía» — ваниль 1.15.2, `company_ynchausti_y_compania`"
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

Вид компании · `company_ynchausti_y_compania` · `common/company_types/00_companies_ip4.txt:347`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_ynchausti_y_compania.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Порты|Порты]], [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]]
- **extension_building_types**: [[vanilla/Здания/Верфи|Верфи]], [[vanilla/Здания/Рисовые поля|Рисовые поля]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 368–373
- **potential**: скрипт, строки 375–378
- **attainable**: скрипт, строки 380–389
- **possible**: скрипт, строки 391–407
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 414–422
- **ai_construction_targets**: скрипт, строки 424–453
- **ai_weight**: скрипт, строки 455–457
