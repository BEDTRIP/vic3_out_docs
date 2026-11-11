---
type: concept
description: "Идеология «Dacianist» — Gates of Bosphorus 1.15, `ideology_gbbf_dacianist`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Dacianist", "ideology_gbbf_dacianist"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_dacianist
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Dacianist

Идеология · `ideology_gbbf_dacianist` · `common/ideologies/gbbf_leader_ideologies.txt:198`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_gbbf_dacianist.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `strongly_disapprove`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `approve`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `approve`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `approve`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `approve`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `strongly_approve`
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `strongly_disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `disapprove`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `strongly_approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `strongly_disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
- **country_trigger**:
  - `country_has_primary_culture` = `cu:romanian`
- **interest_group_leader_trigger**: скрипт, строки 251–261
- **interest_group_leader_weight**: скрипт, строки 262–281
- **non_interest_group_leader_weight**:
  - `value` = `0`
