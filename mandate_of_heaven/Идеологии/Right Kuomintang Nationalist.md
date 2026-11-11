---
type: concept
description: "Идеология «Right Kuomintang Nationalist» — Mandate of Heaven 1.15, `ideology_moh_right_kmt`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Right Kuomintang Nationalist", "ideology_moh_right_kmt"]
tags: [mandate_of_heaven, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_moh_right_kmt
paths: [for addon/Mandate of Heaven/common/ideologies/moh_leader_ideologies.txt]
---
# Right Kuomintang Nationalist

Идеология · `ideology_moh_right_kmt` · `common/ideologies/moh_leader_ideologies.txt:588`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_right_kmt.dds`
- **character_ideology**: `yes`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Общественная администрация|Общественная администрация]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Революционная гвардия|Революционная гвардия]] = `strongly_disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **lawgroup_governance_principles**:
  - [[mandate_of_heaven/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `strongly_approve`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `approve`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `approve`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `approve`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `approve`
  - [[vanilla/Законы/Попечительство|Попечительство]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `approve`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_approve`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `neutral`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `neutral`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `neutral`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `approve`
  - [[vanilla/Законы/Чрезвычайная комиссия|Чрезвычайная комиссия]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `neutral`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `disapprove`
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `neutral`
  - [[vanilla/Законы/Цензура|Цензура]] = `approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `disapprove`
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `disapprove`
- **country_trigger**: скрипт, строки 662–691
- **interest_group_leader_trigger**:
  - `ideology_moh_kmt_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 697–704
- **interest_group_leader_weight**: скрипт, строки 706–728
- **non_interest_group_leader_weight**: скрипт, строки 730–746

## Ссылаются

- **Группы интересов** (character_ideologies): [[mandate_of_heaven/Группы интересов/Вооружённые силы|Вооружённые силы]], [[mandate_of_heaven/Группы интересов/Интеллигенты|Интеллигенты]], [[mandate_of_heaven/Группы интересов/Мелкие буржуа|Мелкие буржуа]]
