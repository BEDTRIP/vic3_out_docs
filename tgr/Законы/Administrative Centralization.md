---
type: concept
description: "Закон «Administrative Centralization» — TGR 1.13, `law_administrative_centralism`"
project: vic3
source: tgr
aliases: ["Administrative Centralization", "law_administrative_centralism"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_administrative_centralism
paths: [TheGreatRevision/common/laws/TGR_POLITICS_centralization.txt]
---
# Administrative Centralization

Закон · `law_administrative_centralism` · `common/laws/TGR_POLITICS_centralization.txt:113`

## Поля

- **group**: [[tgr/Группы законов/Centralization|Centralization]]
- **icon**: `gfx/interface/icons/law_icons/mass_conscription.dds`
- **progressiveness**: `50`
- **modifier**:
  - `country_government_dividends_efficiency_add` = `0.15`
  - `country_government_dividends_reinvestment_add` = `-0.15`
  - `country_bureaucracy_investment_cost_factor_mult` = `0.10`
  - `state_bureaucracy_population_base_cost_factor_mult` = `0.10`
- **disallowing_laws**: [[tgr/Законы/Традиционализм|Традиционализм]], [[tgr/Законы/Аграрность|Аграрность]], [[tgr/Законы/Добывающая экономика|Добывающая экономика]], [[tgr/Законы/Свободная конкуренция|Свободная конкуренция]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: [[tgr/Законы/Интервенционизм|Интервенционизм]]
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 143–151

## Ссылаются

- **Идеологии** (lawgroup_centralization: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
- **Идеологии** (lawgroup_centralization: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
- **Идеологии** (lawgroup_centralization: neutral): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_centralization: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
