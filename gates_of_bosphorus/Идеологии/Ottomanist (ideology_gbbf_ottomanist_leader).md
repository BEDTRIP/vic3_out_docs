---
type: concept
description: "Идеология «Ottomanist (ideology_gbbf_ottomanist_leader)» — Gates of Bosphorus 1.13, `ideology_gbbf_ottomanist_leader`"
project: vic3
source: gates_of_bosphorus
aliases: ["Ottomanist (ideology_gbbf_ottomanist_leader)", "Ottomanist", "ideology_gbbf_ottomanist_leader"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_ottomanist_leader
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Ottomanist (ideology_gbbf_ottomanist_leader)

Идеология · `ideology_gbbf_ottomanist_leader` · `common/ideologies/gbbf_leader_ideologies.txt:1274`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_gbbf_ottomanist_leader.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `neutral`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `approve`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `approve`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `neutral`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `approve`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `neutral`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `approve`
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `neutral`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `disapprove`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `strongly_approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `strongly_disapprove`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `strongly_approve`
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `neutral`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
- **country_trigger**: скрипт, строки 1327–1329
- **interest_group_leader_trigger**:
  - **owner**:
    - `has_journal_entry` = `je_turkfm_tanzimat_main`
  - `ideology_republican_leader_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 1336–1368
- **non_interest_group_leader_trigger**:
  - **owner**:
    - `has_journal_entry` = `je_turkfm_tanzimat_main`
  - `ideology_republican_leader_valid_trigger` = `yes`
- **non_interest_group_leader_weight**: скрипт, строки 1375–1409
