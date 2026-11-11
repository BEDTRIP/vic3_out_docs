---
type: concept
description: "Закон «Public Enterprise 100%» — TGR 1.15, `law_tgr_public_enterprise`"
project: vic3
audience: agent
source: tgr
aliases: ["Public Enterprise 100%", "law_tgr_public_enterprise"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_tgr_public_enterprise
paths: [TheGreatRevision/common/laws/TGR_POLITICS_company_participation.txt]
---
# Public Enterprise 100%

Закон · `law_tgr_public_enterprise` · `common/laws/TGR_POLITICS_company_participation.txt:131`

## Поля

- **group**: [[tgr/Группы законов/Company Nationalization|Company Nationalization]]
- **icon**: `gfx/interface/icons/law_icons/command_economy.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[vanilla/Технологии/Централизованное планирование|Централизованное планирование]]
- **can_enact**: скрипт, строки 136–136
- **on_enact**: скрипт, строки 137–155
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-company-throughput-bonus-add|country_company_throughput_bonus_add]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-company-construction-efficiency-bonus-add|country_company_construction_efficiency_bonus_add]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `0.5`
- **ai_enact_weight_modifier**: скрипт, строки 161–164

## Ссылаются

- **Идеологии** (lawgroup_tgr_company_participation: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]]
- **Идеологии** (lawgroup_tgr_company_participation: strongly_approve): [[tgr/Идеологии/Авангардизм|Авангардизм]], [[tgr/Идеологии/Коммунизм (ideology_communist_leader)|Коммунизм (ideology_communist_leader)]]
- **Идеологии** (lawgroup_tgr_company_participation: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
- **Методы производства** (открывает закон): [[tgr/Методы производства/Public Enterprise 100%|Public Enterprise 100%]]
