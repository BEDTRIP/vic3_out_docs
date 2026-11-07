---
type: concept
description: "Закон «Military Expansionism» — TGR 1.13, `foreign_policy_military_expansionism`"
project: vic3
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
  - `country_military_tech_research_speed_mult` = `0.25`
  - `country_infamy_generation_mult` = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - `unit_experience_gain_mult` = `0.05`
  - `interest_group_ig_armed_forces_pol_str_mult` = `0.05`
  - `interest_group_ig_armed_forces_pop_attraction_mult` = `0.10`
  - `country_officers_pol_str_mult` = `0.20`
  - `country_soldiers_pol_str_mult` = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 142–149

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Пацифизм|Пацифизм]]
- **Идеологии** (lawgroup_foreign_policy: neutral): [[tgr/Идеологии/Протекционист|Протекционист]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Джингоизм|Джингоизм]]
