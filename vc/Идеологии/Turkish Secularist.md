---
type: concept
description: "Идеология «Turkish Secularist» — VC 1.15, `ideology_kemalism_leader`"
project: vic3
audience: agent
source: vc
aliases: ["Turkish Secularist", "ideology_kemalism_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_kemalism_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# Turkish Secularist

Идеология · `ideology_kemalism_leader` · `common/ideologies/joi_leader_ideologies.txt:288`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_republican.dds`
- **character_ideology**: `yes`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `neutral`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_approve`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `approve`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `approve`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `approve`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `strongly_approve`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `strongly_disapprove`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `approve`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `strongly_approve`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `neutral`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `strongly_approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **country_trigger**:
  - `has_variable` = `liberalism_of_turkey_var`
- **interest_group_leader_trigger**:
  - `ideology_communist_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_communist_leader_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 371–394
- **non_interest_group_leader_weight**:
  - `value` = `250`
