---
type: concept
description: "Закон «Economic Centralization» — TGR 1.13, `law_economic_centralism`"
project: vic3
source: tgr
aliases: ["Economic Centralization", "law_economic_centralism"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_economic_centralism
paths: [TheGreatRevision/common/laws/TGR_POLITICS_centralization.txt]
---
# Economic Centralization

Закон · `law_economic_centralism` · `common/laws/TGR_POLITICS_centralization.txt:154`

## Поля

- **group**: [[tgr/Группы законов/Centralization|Centralization]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/armed_isolationism.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.35`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `-0.35`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `0.25`
- **on_enact**: пусто
- **disallowing_laws**: [[tgr/Законы/Традиционализм|Традиционализм]], [[tgr/Законы/Аграрность|Аграрность]], [[tgr/Законы/Добывающая экономика|Добывающая экономика]], [[tgr/Законы/Свободная конкуренция|Свободная конкуренция]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: [[tgr/Законы/Командная экономика|Командная экономика]]
- **unlocking_technologies**: [[vanilla/Технологии/Централизованное планирование|Централизованное планирование]]
- **ai_enact_weight_modifier**: скрипт, строки 188–205

## Ссылаются

- **Идеологии** (lawgroup_centralization: approve): [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
- **Идеологии** (lawgroup_centralization: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_centralization: neutral): [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]]
- **Идеологии** (lawgroup_centralization: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_centralization: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
