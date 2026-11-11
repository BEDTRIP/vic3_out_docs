---
type: concept
description: "Закон «Diplomatic Embassies» — TGR 1.15, `foreign_policy_diplomatic_embassies`"
project: vic3
audience: agent
source: tgr
aliases: ["Diplomatic Embassies", "foreign_policy_diplomatic_embassies"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_diplomatic_embassies
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Diplomatic Embassies

Закон · `foreign_policy_diplomatic_embassies` · `common/laws/TGR_POLITICS_foreign_policy.txt:31`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/mass_conscription.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **disallowing_laws**: [[tgr/Законы/Изоляционизм|Изоляционизм]]
- **unlocking_technologies**: [[tgr/Технологии/Международные отношения|Международные отношения]]
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-infamy-decay-mult|country_infamy_decay_mult]] = `-0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-pol-str-mult|interest_group_ig_intelligentsia_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-pop-attraction-mult|interest_group_ig_intelligentsia_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-influence-add|country_influence_add]] = `50`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-academics-pol-str-mult|country_academics_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 64–71

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_foreign_policy: neutral): [[tgr/Идеологии/Луддит|Луддит]], [[tgr/Идеологии/Суверенизм|Суверенизм]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]]
