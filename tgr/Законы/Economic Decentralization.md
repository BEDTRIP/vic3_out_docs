---
type: concept
description: "Закон «Economic Decentralization» — TGR 1.15, `law_economic_decentralism`"
project: vic3
audience: agent
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
- **on_enact**: скрипт, строки 21–25
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-tax-collection-mult|state_tax_collection_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `-0.25`
- **ai_enact_weight_modifier**: скрипт, строки 33–40

## Ссылаются

- **Идеологии** (lawgroup_centralization: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Революционный социализм|Революционный социализм]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]]
- **Идеологии** (lawgroup_centralization: neutral): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
- **Идеологии** (lawgroup_centralization: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_centralization: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
