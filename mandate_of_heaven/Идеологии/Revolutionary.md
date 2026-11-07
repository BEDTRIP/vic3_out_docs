---
type: concept
description: "Идеология «Revolutionary» — Mandate of Heaven 1.13, `ideology_moh_revolutionary`"
project: vic3
source: mandate_of_heaven
aliases: ["Revolutionary", "ideology_moh_revolutionary"]
tags: [mandate_of_heaven, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_moh_revolutionary
paths: [for addon/Mandate of Heaven/common/ideologies/moh_leader_ideologies.txt]
---
# Revolutionary

Идеология · `ideology_moh_revolutionary` · `common/ideologies/moh_leader_ideologies.txt:197`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_moh_revolutionary.png`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[mandate_of_heaven/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `strongly_approve`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `strongly_approve`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `neutral`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `strongly_approve`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `approve`
  - [[vanilla/Законы/Попечительство|Попечительство]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `neutral`
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `neutral`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `approve`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `approve`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `neutral`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
- **country_trigger**: скрипт, строки 241–276
- **interest_group_leader_trigger**: скрипт, строки 278–286
- **non_interest_group_leader_trigger**: скрипт, строки 288–301
- **interest_group_leader_weight**: скрипт, строки 303–382
- **non_interest_group_leader_weight**: скрипт, строки 384–402

## Ссылаются

- **Группы интересов** (character_ideologies): [[mandate_of_heaven/Группы интересов/Вооружённые силы|Вооружённые силы]], [[mandate_of_heaven/Группы интересов/Интеллигенты|Интеллигенты]], [[mandate_of_heaven/Группы интересов/Мелкие буржуа|Мелкие буржуа]]
