---
type: concept
description: "Вид компании ««Dollfus-Mieg et Cie»» — TGR 1.13, `company_dmc`"
project: vic3
source: tgr
aliases: ["«Dollfus-Mieg et Cie»", "Dollfus-Mieg et Cie", "company_dmc"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_dmc
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Dollfus-Mieg et Cie»]]"
---
# «Dollfus-Mieg et Cie»

Вид компании · `company_dmc` · `common/company_types/TGR_TRADE_companies.txt:1`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **possible**: изменено
- **ai_weight**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_dmc.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BURGUNDY`
- **building_types**: [[tgr/Здания/Текстильные фабрики|Текстильные фабрики]], [[tgr/Здания/Бумажные фабрики|Бумажные фабрики]], [[tgr/Здания/Пищевые производства|Пищевые производства]], [[tgr/Здания/Заводы взрывчатки|Заводы взрывчатки]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_generic_groceries`, `prestige_good_generic_paper`
- **potential**: скрипт, строки 26–28
- **attainable**: скрипт, строки 30–36
- **possible**: скрипт, строки 38–47
- **prosperity_modifier**:
  - `state_assimilation_mult` = `0.1`
- **ai_will_do**: скрипт, строки 53–58
- **ai_construction_targets**: скрипт, строки 60–67
- **ai_weight**: скрипт, строки 69–71
