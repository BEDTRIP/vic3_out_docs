---
type: concept
description: "Закон «Medium Nationalization 25%» — TGR 1.15, `law_tgr_strategic_participation`"
project: vic3
audience: agent
source: tgr
aliases: ["Medium Nationalization 25%", "law_tgr_strategic_participation"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_tgr_strategic_participation
paths: [TheGreatRevision/common/laws/TGR_POLITICS_company_participation.txt]
---
# Medium Nationalization 25%

Закон · `law_tgr_strategic_participation` · `common/laws/TGR_POLITICS_company_participation.txt:60`

## Поля

- **group**: [[tgr/Группы законов/Company Nationalization|Company Nationalization]]
- **icon**: `gfx/interface/icons/law_icons/interventionism.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[vanilla/Технологии/Центральный архив|Центральный архив]]
- **can_enact**: скрипт, строки 65–65
- **on_enact**: скрипт, строки 66–84
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-company-throughput-bonus-add|country_company_throughput_bonus_add]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-company-construction-efficiency-bonus-add|country_company_construction_efficiency_bonus_add]] = `-0.5`
- **ai_enact_weight_modifier**: скрипт, строки 89–92

## Ссылаются

- **Идеологии** (lawgroup_tgr_company_participation: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]]
- **Идеологии** (lawgroup_tgr_company_participation: disapprove): [[tgr/Идеологии/Анархизм|Анархизм]]
- **Идеологии** (lawgroup_tgr_company_participation: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Авангардизм|Авангардизм]], [[tgr/Идеологии/Коммунизм (ideology_communist_leader)|Коммунизм (ideology_communist_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
- **Методы производства** (открывает закон): [[tgr/Методы производства/Medium Nationalization 25%|Medium Nationalization 25%]]
