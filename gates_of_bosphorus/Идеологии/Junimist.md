---
type: concept
description: "Идеология «Junimist» — Gates of Bosphorus 1.13, `ideology_gbbf_junimist`"
project: vic3
source: gates_of_bosphorus
aliases: ["Junimist", "ideology_gbbf_junimist"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_junimist
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Junimist

Идеология · `ideology_gbbf_junimist` · `common/ideologies/gbbf_leader_ideologies.txt:548`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_gbbf_junimist.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `approve`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `neutral`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `approve`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `approve`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `disapprove`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `approve`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `approve`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `strongly_disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `neutral`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `strongly_disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `disapprove`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `approve`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `strongly_approve`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
- **country_trigger**:
  - `country_has_primary_culture` = `cu:romanian`
- **interest_group_leader_trigger**: скрипт, строки 596–605
- **interest_group_leader_weight**: скрипт, строки 606–623
- **non_interest_group_leader_weight**:
  - `value` = `0`
