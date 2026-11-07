---
type: concept
description: "Идеология «Феминизм (ideology_feminist)» — BPM 1.13, `ideology_feminist`"
project: vic3
source: bpm
aliases: ["Феминизм (ideology_feminist)", "Feminist", "ideology_feminist"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_feminist
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
replaces: "[[vanilla/Идеологии/Феминизм (ideology_feminist)]]"
---
# Феминизм (ideology_feminist)

Идеология · `ideology_feminist` · `common/ideologies/bpm_leader_ideologies.txt:1600` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **show_in_list**: добавлено
- **interest_group_leader_trigger**: изменено
- **interest_group_leader_weight**: изменено
- **non_interest_group_leader_trigger**: изменено
- **non_interest_group_leader_weight**: изменено
- **country_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_womens_liberation.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_rights_of_women**:
  - [[bpm/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `neutral`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `disapprove`
  - [[vanilla/Законы/Попечительство|Попечительство]] = `strongly_disapprove`
- **interest_group_leader_trigger**: скрипт, строки 1613–1620
- **interest_group_leader_weight**: скрипт, строки 1622–1689
- **non_interest_group_leader_trigger**: скрипт, строки 1691–1707
- **non_interest_group_leader_weight**: скрипт, строки 1709–1732
