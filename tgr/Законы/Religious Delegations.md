---
type: concept
description: "Закон «Religious Delegations» — TGR 1.13, `foreign_policy_religious_embassies`"
project: vic3
audience: agent
source: tgr
aliases: ["Religious Delegations", "foreign_policy_religious_embassies"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_religious_embassies
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Religious Delegations

Закон · `foreign_policy_religious_embassies` · `common/laws/TGR_POLITICS_foreign_policy.txt:236`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/freedom_of_conscience.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **disallowing_laws**: [[tgr/Законы/Полное разделение|Полное разделение]], [[tgr/Законы/Государственный атеизм|Государственный атеизм]]
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-improve-relations-speed-mult|country_improve_relations_speed_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-violent-hostility-mult|state_radicalism_increases_violent_hostility_mult]] = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-conversion-mult|state_conversion_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pol-str-mult|interest_group_ig_devout_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pop-attraction-mult|interest_group_ig_devout_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-clergymen-pol-str-mult|country_clergymen_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-farmers-pol-str-mult|country_farmers_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 271–278

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Луддит|Луддит]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]]
