---
type: concept
description: "Закон «Low Nationalization 10%» — TGR 1.15, `law_tgr_public_dividend`"
project: vic3
audience: agent
source: tgr
aliases: ["Low Nationalization 10%", "law_tgr_public_dividend"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_tgr_public_dividend
paths: [TheGreatRevision/common/laws/TGR_POLITICS_company_participation.txt]
---
# Low Nationalization 10%

Закон · `law_tgr_public_dividend` · `common/laws/TGR_POLITICS_company_participation.txt:25`

## Поля

- **group**: [[tgr/Группы законов/Company Nationalization|Company Nationalization]]
- **icon**: `gfx/interface/icons/law_icons/interventionism.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: [[tgr/Технологии/Централизация|Централизация]]
- **can_enact**: скрипт, строки 30–30
- **on_enact**: скрипт, строки 31–49
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-company-throughput-bonus-add|country_company_throughput_bonus_add]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-company-construction-efficiency-bonus-add|country_company_construction_efficiency_bonus_add]] = `-0.25`
- **ai_enact_weight_modifier**: скрипт, строки 54–57

## Ссылаются

- **Идеологии** (lawgroup_tgr_company_participation: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
- **Идеологии** (lawgroup_tgr_company_participation: disapprove): [[tgr/Идеологии/Авангардизм|Авангардизм]], [[tgr/Идеологии/Коммунизм (ideology_communist_leader)|Коммунизм (ideology_communist_leader)]]
- **Идеологии** (lawgroup_tgr_company_participation: neutral): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Анархизм|Анархизм]]
- **Методы производства** (открывает закон): [[tgr/Методы производства/Low Nationalization 10%|Low Nationalization 10%]]
