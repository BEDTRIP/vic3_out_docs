---
type: concept
description: "Идеология «Этнонационализм (ideology_ethno_nationalist)» — ваниль 1.13, `ideology_ethno_nationalist`"
project: vic3
source: vanilla
aliases: ["Этнонационализм (ideology_ethno_nationalist)", "Ethno-Nationalist", "ideology_ethno_nationalist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_ethno_nationalist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Этнонационализм (ideology_ethno_nationalist)

Идеология · `ideology_ethno_nationalist` · `common/ideologies/01_character_ideologies.txt:5538`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_ethno_nationalist.dds`
- **character_ideology**: `yes`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_approve`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `approve`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `approve`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `disapprove`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_disapprove`
- **lawgroup_migration**:
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `strongly_approve`
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `approve`
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `disapprove`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Паннационализм|Паннационализм]]
- **interest_group_leader_trigger**:
  - `ideology_ethno_nationalist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 5566–5578
- **interest_group_leader_weight**: скрипт, строки 5580–5700
- **non_interest_group_leader_weight**: скрипт, строки 5702–5801
