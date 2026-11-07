---
type: concept
description: "Идеология «Reactionary Absolutist» — VC 1.13, `ideology_reactionism_leader`"
project: vic3
audience: agent
source: vc
aliases: ["Reactionary Absolutist", "ideology_reactionism_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_reactionism_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# Reactionary Absolutist

Идеология · `ideology_reactionism_leader` · `common/ideologies/joi_leader_ideologies.txt:509`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_despotic_utopian.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `neutral`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `neutral`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `strongly_disapprove`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `disapprove`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `neutral`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_approve`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `neutral`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `disapprove`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_approve`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `strongly_approve`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `approve`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `disapprove`
  - [[vanilla/Законы/Цензура|Цензура]] = `approve`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_approve`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `approve`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `approve`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `strongly_approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `neutral`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `neutral`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
- **country_trigger**:
  - `has_variable` = `government_leader_government_leader_nicholas_i_var`
- **interest_group_leader_trigger**:
  - `ideology_slaver_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_slaver_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 605–619
- **non_interest_group_leader_weight**:
  - `value` = `25`
