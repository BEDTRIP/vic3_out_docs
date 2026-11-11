---
type: concept
description: "Вид компании ««Sherkat-e Eslamiya»» — TGR 1.15, `company_sherkate_eslamiya`"
project: vic3
audience: agent
source: tgr
aliases: ["«Sherkat-e Eslamiya»", "Sherkat-e Eslamiya", "company_sherkate_eslamiya"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sherkate_eslamiya
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Sherkat-e Eslamiya»]]"
---
# «Sherkat-e Eslamiya»

Вид компании · `company_sherkate_eslamiya` · `common/company_types/TGR_TRADE_companies.txt:1157`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **possible**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/historical_serkat_e_eslamiya.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ISFAHAN`
- **building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Маковые плантации|Маковые плантации]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_generic_grain`, `prestige_good_generic_opium`
- **potential**: скрипт, строки 1180–1182
- **attainable**: скрипт, строки 1184–1190
- **possible**: скрипт, строки 1192–1200
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-state-religion-wages-mult|country_state_religion_wages_mult]] = `0.2`
- **ai_will_do**: скрипт, строки 1206–1211
- **ai_construction_targets**: скрипт, строки 1213–1220
- **ai_weight**: скрипт, строки 1222–1224
- **prestige_goods_trigger**: скрипт, строки 1226–1231
