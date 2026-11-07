---
type: concept
description: "Вид компании ««United Fruit Company»» — TGR 1.13, `company_united_fruit`"
project: vic3
audience: agent
source: tgr
aliases: ["«United Fruit Company»", "United Fruit Company", "company_united_fruit"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_united_fruit
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«United Fruit Company»]]"
---
# «United Fruit Company»

Вид компании · `company_united_fruit` · `common/company_types/TGR_TRADE_companies.txt:1310`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **potential**: изменено
- **possible**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_united_fruit_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MEXICO`
- **building_types**: [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]], [[vanilla/Здания/Банановые плантации|Банановые плантации]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_gros_michel_banana`
- **potential**: пусто
- **possible**: скрипт, строки 1337–1352
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-infamy-decay-mult|country_infamy_decay_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 1359–1364
- **ai_construction_targets**: скрипт, строки 1366–1376
- **ai_weight**: скрипт, строки 1378–1380
