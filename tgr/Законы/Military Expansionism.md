---
type: concept
description: "Закон «Military Expansionism» — TGR 1.15, `foreign_policy_military_expansionism`"
project: vic3
audience: agent
source: tgr
aliases: ["Military Expansionism", "foreign_policy_military_expansionism"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_military_expansionism
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Military Expansionism

Закон · `foreign_policy_military_expansionism` · `common/laws/TGR_POLITICS_foreign_policy.txt:113`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/territorial_expansion.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-military-tech-research-speed-mult|country_military_tech_research_speed_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-infamy-generation-mult|country_infamy_generation_mult]] = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-experience-gain-mult|unit_experience_gain_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-armed-forces-pol-str-mult|interest_group_ig_armed_forces_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-armed-forces-pop-attraction-mult|interest_group_ig_armed_forces_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-soldiers-pol-str-mult|country_soldiers_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 142–149

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]]
