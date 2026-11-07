---
type: concept
description: "Идеология «Карлизм (ideology_carlist)» — ваниль 1.13, `ideology_carlist`"
project: vic3
source: vanilla
aliases: ["Карлизм (ideology_carlist)", "Carlist", "ideology_carlist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_carlist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Карлизм (ideology_carlist)

Идеология · `ideology_carlist` · `common/ideologies/01_character_ideologies.txt:10595`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_carlist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `approve`
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `strongly_approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `neutral`
  - [[vanilla/Законы/Подданство|Подданство]] = `approve`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `neutral`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 10649–10664
- **interest_group_leader_trigger**:
  - `ideology_carlist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 10670–10685
- **interest_group_leader_weight**: скрипт, строки 10687–10778
- **non_interest_group_leader_weight**: скрипт, строки 10780–10859
