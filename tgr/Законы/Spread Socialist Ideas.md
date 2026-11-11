---
type: concept
description: "Закон «Spread Socialist Ideas» — TGR 1.15, `foreign_policy_socialist_ideas`"
project: vic3
audience: agent
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
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-ideological-incoherence-mult|country_legitimacy_ideological_incoherence_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-society-tech-research-speed-mult|country_society_tech_research_speed_mult]] = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-trade-unions-pol-str-mult|interest_group_ig_trade_unions_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-trade-unions-pop-attraction-mult|interest_group_ig_trade_unions_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-laborers-pol-str-mult|country_laborers_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-machinists-pol-str-mult|country_machinists_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 361–368

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
