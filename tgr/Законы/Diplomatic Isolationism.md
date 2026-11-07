---
type: concept
description: "Закон «Diplomatic Isolationism» — TGR 1.13, `foreign_policy_diplomatic_isolationism`"
project: vic3
audience: agent
source: tgr
aliases: ["Diplomatic Isolationism", "foreign_policy_diplomatic_isolationism"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_diplomatic_isolationism
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Diplomatic Isolationism

Закон · `foreign_policy_diplomatic_isolationism` · `common/laws/TGR_POLITICS_foreign_policy.txt:281`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/closed_borders.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **disallowing_laws**: [[tgr/Законы/Свободная торговля|Свободная торговля]], [[tgr/Законы/Миграция не контролируется|Миграция не контролируется]]
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-resistance-mult|country_support_separatism_resistance_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-improve-relations-speed-mult|country_improve_relations_speed_mult]] = `-0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-cost-mult|building_nationalization_cost_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-rural-folk-pol-str-mult|interest_group_ig_rural_folk_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-rural-folk-pop-attraction-mult|interest_group_ig_rural_folk_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-farmers-pol-str-mult|country_farmers_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-peasants-pol-str-mult|country_peasants_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 316–323

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Луддит|Луддит]], [[tgr/Идеологии/Пацифизм|Пацифизм]], [[tgr/Идеологии/Суверенизм|Суверенизм]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Джингоизм|Джингоизм]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
- **Идеологии** (lawgroup_foreign_policy: neutral): [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Протекционист|Протекционист]]
