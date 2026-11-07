---
type: concept
description: "Закон «Reinforces Foreign perception» — TGR 1.13, `foreign_policy_authoritarian_representation`"
project: vic3
source: tgr
aliases: ["Reinforces Foreign perception", "foreign_policy_authoritarian_representation"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_authoritarian_representation
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Reinforces Foreign perception

Закон · `foreign_policy_authoritarian_representation` · `common/laws/TGR_POLITICS_foreign_policy.txt:74`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/autocracy.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-radicals-from-legitimacy-mult|country_radicals_from_legitimacy_mult]] = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pol-str-mult|interest_group_ig_landowners_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pop-attraction-mult|interest_group_ig_landowners_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `50`
  - [[vanilla/движок/Модификаторы C#^m-country-aristocrats-pol-str-mult|country_aristocrats_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 103–110

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Джингоизм|Джингоизм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Пацифизм|Пацифизм]]
- **Идеологии** (lawgroup_foreign_policy: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
