---
type: concept
description: "Идеология «Reactionary Distributist» — BPM 1.13, `ideology_reactionary_anti_capitalist`"
project: vic3
audience: agent
source: bpm
aliases: ["Reactionary Distributist", "ideology_reactionary_anti_capitalist"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_reactionary_anti_capitalist
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
---
# Reactionary Distributist

Идеология · `ideology_reactionary_anti_capitalist` · `common/ideologies/bpm_leader_ideologies.txt:9590`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/unused/ideology_leader_reactionary.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_church_and_state**:
  - [[bpm/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[bpm/Законы/Свобода совести|Свобода совести]] = `approve`
  - [[bpm/Законы/Секуляризм|Секуляризм]] = `strongly_disapprove`
  - [[bpm/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `strongly_approve`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `approve`
  - [[bpm/Законы/Изоляционизм|Изоляционизм]] = `disapprove`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
  - [[bpm/Законы/Религиозные школы|Религиозные школы]] = `strongly_approve`
  - [[bpm/Законы/Частные школы|Частные школы]] = `neutral`
  - [[bpm/Законы/Государственные школы|Государственные школы]] = `approve`
- **lawgroup_labor_rights**:
  - [[bpm/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `neutral`
  - [[bpm/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[bpm/Законы/Защита прав рабочих|Защита прав рабочих]] = `strongly_approve`
- **lawgroup_economic_system**:
  - [[bpm/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[bpm/Законы/Интервенционизм|Интервенционизм]] = `approve`
  - [[bpm/Законы/Аграрность|Аграрность]] = `strongly_approve`
  - [[bpm/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_approve`
  - [[bpm/Законы/Свободная конкуренция|Свободная конкуренция]] = `neutral`
  - [[bpm/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_approve`
  - [[bpm/Законы/Командная экономика|Командная экономика]] = `disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[bpm/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[bpm/Законы/Арендаторы|Арендаторы]] = `approve`
  - [[bpm/Законы/Крестьянское хозяйство|Крестьянское хозяйство]] = `approve`
  - [[bpm/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
  - [[bpm/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `neutral`
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_approve`
- **interest_group_leader_trigger**: скрипт, строки 9649–9656
- **interest_group_leader_weight**: скрипт, строки 9658–9718
- **non_interest_group_leader_trigger**: скрипт, строки 9720–9740
- **non_interest_group_leader_weight**:
  - `value` = `50`
