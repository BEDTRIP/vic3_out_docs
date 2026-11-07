---
type: concept
description: "Идеология «Технократ (ideology_positivist)» — BPM 1.13, `ideology_positivist`"
project: vic3
source: bpm
aliases: ["Технократ (ideology_positivist)", "Technocrat", "ideology_positivist"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_positivist
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
replaces: "[[vanilla/Идеологии/Позитивист (ideology_positivist)]]"
---
# Технократ (ideology_positivist)

Идеология · `ideology_positivist` · `common/ideologies/bpm_leader_ideologies.txt:6595` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **show_in_list**: добавлено
- **lawgroup_governance_principles**: изменено
- **lawgroup_legislative_principles**: добавлено
- **lawgroup_church_and_state**: изменено
- **lawgroup_distribution_of_power**: изменено
- **lawgroup_repeatable_religion**: добавлено
- **interest_group_leader_trigger**: изменено
- **interest_group_leader_weight**: изменено
- **non_interest_group_leader_trigger**: изменено
- **non_interest_group_leader_weight**: изменено
- **country_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_positivist.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_governance_principles**:
  - [[bpm/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[bpm/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[bpm/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[bpm/Законы/Республика (law_parliamentary_republic)|Республика (law_parliamentary_republic)]] = `neutral`
  - [[bpm/Законы/Республика (law_presidential_republic)|Республика (law_presidential_republic)]] = `approve`
- **lawgroup_legislative_principles**:
  - [[bpm/Законы/Совещательный орган|Совещательный орган]] = `neutral`
  - [[bpm/Законы/Разделение властей|Разделение властей]] = `neutral`
  - [[bpm/Законы/Верховный законодательный орган|Верховный законодательный орган]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[bpm/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[bpm/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[bpm/Законы/Секуляризм|Секуляризм]] = `approve`
  - [[bpm/Законы/Государственный атеизм|Государственный атеизм]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[bpm/Законы/Технократия|Технократия]] = `strongly_approve`
  - [[bpm/Законы/Военная хунта|Военная хунта]] = `neutral`
  - [[bpm/Законы/Голосуют богатые|Голосуют богатые]] = `approve`
  - [[bpm/Законы/Автократия|Автократия]] = `neutral`
  - [[bpm/Законы/Олигархия|Олигархия]] = `neutral`
  - [[bpm/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[bpm/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[bpm/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[bpm/Законы/Анархия|Анархия]] = `strongly_disapprove`
- **lawgroup_bureaucracy**:
  - [[bpm/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `strongly_approve`
  - [[bpm/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[bpm/Законы/Потомственные чиновники|Потомственные чиновники]] = `strongly_disapprove`
- **lawgroup_repeatable_religion**:
  - [[bpm/Законы/Продвижение государственной религии|Продвижение государственной религии]] = `strongly_disapprove`
  - [[bpm/Законы/Антисветская реакция|Антисветская реакция]] = `strongly_disapprove`
  - [[bpm/Законы/Продвижение светских ценностей|Продвижение светских ценностей]] = `strongly_approve`
  - [[bpm/Законы/Антирелигиозное насилие|Антирелигиозное насилие]] = `approve`
- **interest_group_leader_trigger**: скрипт, строки 6646–6667
- **interest_group_leader_weight**: скрипт, строки 6669–6751
- **non_interest_group_leader_trigger**: скрипт, строки 6753–6799
- **non_interest_group_leader_weight**:
  - `value` = `10`

## Ссылаются

- **Группы интересов** (character_ideologies): [[bpm/Группы интересов/Консерваторы|Консерваторы]], [[bpm/Группы интересов/Национал-либералы|Национал-либералы]], [[bpm/Группы интересов/Рыночные либералы|Рыночные либералы]]
