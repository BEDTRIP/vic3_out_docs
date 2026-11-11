---
type: concept
description: "Закон «High Nationalization 50%» — TGR 1.15, `law_tgr_shared_prosperity`"
project: vic3
audience: agent
source: tgr
aliases: ["High Nationalization 50%", "law_tgr_shared_prosperity"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_tgr_shared_prosperity
paths: [TheGreatRevision/common/laws/TGR_POLITICS_company_participation.txt]
---
# High Nationalization 50%

Закон · `law_tgr_shared_prosperity` · `common/laws/TGR_POLITICS_company_participation.txt:95`

## Поля

- **group**: [[tgr/Группы законов/Company Nationalization|Company Nationalization]]
- **icon**: `gfx/interface/icons/law_icons/cooperative_ownership.dds`
- **progressiveness**: `75`
- **unlocking_technologies**: [[vanilla/Технологии/Удостоверения личности|Удостоверения личности]]
- **can_enact**: скрипт, строки 100–100
- **on_enact**: скрипт, строки 101–119
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-company-throughput-bonus-add|country_company_throughput_bonus_add]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-company-construction-efficiency-bonus-add|country_company_construction_efficiency_bonus_add]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `0.25`
- **ai_enact_weight_modifier**: скрипт, строки 125–128

## Ссылаются

- **Идеологии** (lawgroup_tgr_company_participation: approve): [[tgr/Идеологии/Авангардизм|Авангардизм]], [[tgr/Идеологии/Коммунизм (ideology_communist_leader)|Коммунизм (ideology_communist_leader)]]
- **Идеологии** (lawgroup_tgr_company_participation: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
- **Идеологии** (lawgroup_tgr_company_participation: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]]
- **Идеологии** (lawgroup_tgr_company_participation: strongly_disapprove): [[tgr/Идеологии/Анархизм|Анархизм]]
- **Методы производства** (открывает закон): [[tgr/Методы производства/High Nationalization 50%|High Nationalization 50%]]
