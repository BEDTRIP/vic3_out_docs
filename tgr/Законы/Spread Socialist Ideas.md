---
type: concept
description: "Закон «Spread Socialist Ideas» — TGR 1.13, `foreign_policy_socialist_ideas`"
project: vic3
source: tgr
aliases: ["Spread Socialist Ideas", "foreign_policy_socialist_ideas"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_socialist_ideas
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Spread Socialist Ideas

Закон · `foreign_policy_socialist_ideas` · `common/laws/TGR_POLITICS_foreign_policy.txt:326`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/anarchy.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **disallowing_laws**: [[tgr/Законы/Монархия|Монархия]], [[tgr/Законы/Вождество|Вождество]]
- **unlocking_technologies**: [[vanilla/Технологии/Социализм|Социализм]]
- **modifier**:
  - `country_legitimacy_ideological_incoherence_mult` = `0.25`
  - `country_society_tech_research_speed_mult` = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - `country_leverage_generation_mult` = `0.05`
  - `interest_group_ig_trade_unions_pol_str_mult` = `0.05`
  - `interest_group_ig_trade_unions_pop_attraction_mult` = `0.10`
  - `country_laborers_pol_str_mult` = `0.20`
  - `country_machinists_pol_str_mult` = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 361–368

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]]
