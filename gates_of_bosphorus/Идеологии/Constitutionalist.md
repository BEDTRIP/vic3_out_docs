---
type: concept
description: "Идеология «Constitutionalist» — Gates of Bosphorus 1.15, `ideology_gbbf_constitutionalist`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Constitutionalist", "ideology_gbbf_constitutionalist"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_constitutionalist
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Constitutionalist

Идеология · `ideology_gbbf_constitutionalist` · `common/ideologies/gbbf_leader_ideologies.txt:98`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_gbbf_constitutionalist.dds`
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
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `approve`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `approve`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `strongly_disapprove`
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `approve`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `approve`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `strongly_disapprove`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `strongly_disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_approve`
- **country_trigger**: скрипт, строки 139–141
- **interest_group_leader_trigger**: скрипт, строки 142–158
- **interest_group_leader_weight**: скрипт, строки 159–192
- **non_interest_group_leader_weight**:
  - `value` = `0`
