---
type: concept
description: "Идеология «Kuomintang Nationalist» — Mandate of Heaven 1.15, `ideology_moh_kmt`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Kuomintang Nationalist", "ideology_moh_kmt"]
tags: [mandate_of_heaven, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_moh_kmt
paths: [for addon/Mandate of Heaven/common/ideologies/moh_leader_ideologies.txt]
---
# Kuomintang Nationalist

Идеология · `ideology_moh_kmt` · `common/ideologies/moh_leader_ideologies.txt:433`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_moh_revolutionary_kmt.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `strongly_disapprove`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Общественная администрация|Общественная администрация]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Революционная гвардия|Революционная гвардия]] = `strongly_disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Чрезвычайная комиссия|Чрезвычайная комиссия]] = `strongly_disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
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
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `approve`
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `approve`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `neutral`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `approve`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
- **country_trigger**: скрипт, строки 493–522
- **interest_group_leader_trigger**:
  - `ideology_moh_kmt_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 528–535
- **interest_group_leader_weight**: скрипт, строки 537–566
- **non_interest_group_leader_weight**: скрипт, строки 568–584

## Ссылаются

- **Группы интересов** (character_ideologies): [[mandate_of_heaven/Группы интересов/Вооружённые силы|Вооружённые силы]], [[mandate_of_heaven/Группы интересов/Интеллигенты|Интеллигенты]], [[mandate_of_heaven/Группы интересов/Мелкие буржуа|Мелкие буржуа]], [[mandate_of_heaven/Группы интересов/Селяне|Селяне]]
