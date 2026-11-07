---
type: concept
description: "Идеология «Либерализм (ideology_liberal_leader)» — ваниль 1.13, `ideology_liberal_leader`"
project: vic3
source: vanilla
aliases: ["Либерализм (ideology_liberal_leader)", "Liberal", "ideology_liberal_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_liberal_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Либерализм (ideology_liberal_leader)

Идеология · `ideology_liberal_leader` · `common/ideologies/01_character_ideologies.txt:8825`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_liberal.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `approve`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `approve`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `strongly_disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `strongly_approve`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `neutral`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Цензура|Цензура]] = `neutral`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `disapprove`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Демократия|Демократия]]
- **non_interest_group_leader_trigger**: скрипт, строки 8866–8880
- **interest_group_leader_weight**: скрипт, строки 8882–9009
- **non_interest_group_leader_weight**: скрипт, строки 9011–9114
