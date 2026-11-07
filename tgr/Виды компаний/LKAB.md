---
type: concept
description: "Вид компании «LKAB» — TGR 1.13, `company_lkab`"
project: vic3
source: tgr
aliases: ["LKAB", "company_lkab"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lkab
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/LKAB]]"
---
# LKAB

Вид компании · `company_lkab` · `common/company_types/TGR_TRADE_companies.txt:878`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **possible**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено
- **category**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/lkab.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NORRLAND`
- **building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Рыболовные верфи|Рыболовные верфи]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_generic_fish`, `prestige_good_swedish_bar_iron`
- **potential**: скрипт, строки 903–905
- **attainable**: скрипт, строки 907–913
- **possible**: скрипт, строки 915–923
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-iron-mine-throughput-add|building_iron_mine_throughput_add]] = `0.2` → [[vanilla/Здания/Железные рудники|Железные рудники]]
- **ai_will_do**: скрипт, строки 929–934
- **ai_construction_targets**: скрипт, строки 936–943
- **ai_weight**: скрипт, строки 945–947
