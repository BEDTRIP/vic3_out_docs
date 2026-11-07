---
type: concept
description: "Закон «Invite Foreign Investors» — TGR 1.13, `foreign_policy_foreign_investments`"
project: vic3
source: tgr
aliases: ["Invite Foreign Investors", "foreign_policy_foreign_investments"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: foreign_policy_foreign_investments
paths: [TheGreatRevision/common/laws/TGR_POLITICS_foreign_policy.txt]
---
# Invite Foreign Investors

Закон · `foreign_policy_foreign_investments` · `common/laws/TGR_POLITICS_foreign_policy.txt:152`

## Поля

- **group**: [[tgr/Группы законов/Foreign Policy|Foreign Policy]]
- **icon**: `gfx/interface/icons/law_icons/no_migration_controls.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **disallowing_laws**: [[tgr/Законы/Изоляционизм|Изоляционизм]]
- **unlocking_technologies**: [[tgr/Технологии/Международные отношения|Международные отношения]]
- **modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-cost-mult|building_nationalization_cost_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `0.25`
- **institution**: `institution_foreign`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-capitalists-investment-pool-efficiency-mult|state_capitalists_investment_pool_efficiency_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pop-attraction-mult|interest_group_ig_industrialists_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-shopkeepers-pol-str-mult|country_shopkeepers_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-engineers-pol-str-mult|country_engineers_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 186–193

## Ссылаются

- **Идеологии** (lawgroup_foreign_policy: approve): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]]
- **Идеологии** (lawgroup_foreign_policy: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Луддит|Луддит]], [[tgr/Идеологии/Протекционист|Протекционист]], [[tgr/Идеологии/Суверенизм|Суверенизм]]
- **Идеологии** (lawgroup_foreign_policy: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
