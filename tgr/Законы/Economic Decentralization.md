---
type: concept
description: "Закон «Economic Decentralization» — TGR 1.13, `law_economic_decentralism`"
project: vic3
source: tgr
aliases: ["Economic Decentralization", "law_economic_decentralism"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_economic_decentralism
paths: [TheGreatRevision/common/laws/TGR_POLITICS_centralization.txt]
---
# Economic Decentralization

Закон · `law_economic_decentralism` · `common/laws/TGR_POLITICS_centralization.txt:1`

## Поля

- **group**: [[tgr/Группы законов/Centralization|Centralization]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/territorial_expansion.dds`
- **progressiveness**: `50`
- **disallowing_laws**: [[tgr/Законы/Интервенционизм|Интервенционизм]], [[tgr/Законы/Командная экономика|Командная экономика]]
- **unlocking_laws**: [[tgr/Законы/Свободная конкуренция|Свободная конкуренция]], [[tgr/Законы/Вождество|Вождество]]
- **unlocking_technologies**: пусто
- **on_enact**: пусто
- **modifier**:
  - `state_tax_collection_mult` = `-0.10`
  - `country_bureaucracy_investment_cost_factor_mult` = `-0.25`
  - `state_bureaucracy_population_base_cost_factor_mult` = `-0.25`
- **ai_enact_weight_modifier**: скрипт, строки 31–38

## Ссылаются

- **Идеологии** (lawgroup_centralization: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]]
- **Идеологии** (lawgroup_centralization: neutral): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
- **Идеологии** (lawgroup_centralization: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_centralization: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
