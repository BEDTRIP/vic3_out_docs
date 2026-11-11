---
type: concept
description: "Закон «Administrative Decentralization» — TGR 1.15, `law_administrative_decentralism`"
project: vic3
audience: agent
source: tgr
aliases: ["Administrative Decentralization", "law_administrative_decentralism"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_administrative_decentralism
paths: [TheGreatRevision/common/laws/TGR_POLITICS_centralization.txt]
---
# Administrative Decentralization

Закон · `law_administrative_decentralism` · `common/laws/TGR_POLITICS_centralization.txt:43`

## Поля

- **group**: [[tgr/Группы законов/Centralization|Centralization]]
- **icon**: `gfx/interface/icons/institution_icons/colonization.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-tax-collection-mult|state_tax_collection_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `-0.10`
- **disallowing_laws**: [[tgr/Законы/Командная экономика|Командная экономика]]
- **unlocking_laws**: пусто
- **on_enact**: скрипт, строки 64–68
- **ai_enact_weight_modifier**: скрипт, строки 70–78

## Ссылаются

- **Идеологии** (lawgroup_centralization: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
- **Идеологии** (lawgroup_centralization: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Революционный социализм|Революционный социализм]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
- **Идеологии** (lawgroup_centralization: neutral): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]]
- **Идеологии** (lawgroup_centralization: strongly_approve): [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
