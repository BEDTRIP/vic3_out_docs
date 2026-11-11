---
type: concept
description: "Идеология «Islamist (ideology_gbbf_islamist_leader)» — Gates of Bosphorus 1.15, `ideology_gbbf_islamist_leader`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Islamist (ideology_gbbf_islamist_leader)", "Islamist", "ideology_gbbf_islamist_leader"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_islamist_leader
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Islamist (ideology_gbbf_islamist_leader)

Идеология · `ideology_gbbf_islamist_leader` · `common/ideologies/gbbf_leader_ideologies.txt:287`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_gbbf_islamist_leader.dds`
- **character_ideology**: `yes`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Попечительство|Попечительство]] = `approve`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `neutral`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `disapprove`
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `strongly_approve`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `disapprove`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `neutral`
- **country_trigger**: скрипт, строки 310–312
- **interest_group_leader_trigger**:
  - **owner**:
    - `has_journal_entry` = `je_turkfm_tanzimat_main`
  - `ideology_traditionalist_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 319–353
- **non_interest_group_leader_trigger**:
  - **owner**:
    - `has_journal_entry` = `je_turkfm_tanzimat_main`
  - **interest_group**:
    - `ideology_traditionalist_valid_trigger` = `yes`
- **non_interest_group_leader_weight**: скрипт, строки 362–396
