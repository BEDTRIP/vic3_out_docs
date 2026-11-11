---
type: concept
description: "Закон «National Sovranism» — TGR 1.15, `foreign_policy_sovranist_policy`"
project: vic3
audience: agent
source: tgr
aliases: ["National Sovranism", "foreign_policy_sovranist_policy"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_sovranist_policy
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# National Sovranism

Закон · `foreign_policy_sovranist_policy` · `common/laws/TGR_POLITICS_foreign_policy.txt:196`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/national_supremacy.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: [[vanilla/Технологии/Национализм|Национализм]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-violent-hostility-mult|state_radicalism_increases_violent_hostility_mult]] = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-wage-full-acceptance-mult|country_wage_full_acceptance_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-petty-bourgeoisie-pol-str-mult|interest_group_ig_petty_bourgeoisie_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-petty-bourgeoisie-pop-attraction-mult|interest_group_ig_petty_bourgeoisie_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-shopkeepers-pol-str-mult|country_shopkeepers_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-clerks-pol-str-mult|country_clerks_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 226–233

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
- **Идеологии** (lawgroup_foreign_policy: neutral): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Суверенизм|Суверенизм]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
