---
type: concept
description: "Идеология «Pan-Indianist (ideology_usfp_pan_indianist)» — Hail Columbia 1.13, `ideology_usfp_pan_indianist`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Pan-Indianist (ideology_usfp_pan_indianist)", "Pan-Indianist", "ideology_usfp_pan_indianist"]
tags: [hail_columbia, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_usfp_pan_indianist
paths: [for addon/Hail Columbia/common/ideologies/usfp_leader_ideologies.txt]
---
# Pan-Indianist (ideology_usfp_pan_indianist)

Идеология · `ideology_usfp_pan_indianist` · `common/ideologies/usfp_leader_ideologies.txt:1188`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_usfp_pan_indianist.dds`
- **character_ideology**: `yes`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `approve`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `strongly_disapprove`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `strongly_disapprove`
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Подданство|Подданство]] = `neutral`
  - [[hail_columbia/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `strongly_approve`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `neutral`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[hail_columbia/Законы/Свобода совести|Свобода совести]] = `approve`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `neutral`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_approve`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `strongly_disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `neutral`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `neutral`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `neutral`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `approve`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `approve`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_approve`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_migration**:
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `disapprove`
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `approve`
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `neutral`
- **country_trigger**: скрипт, строки 1242–1252
- **interest_group_leader_trigger**:
  - `is_interest_group_type` = [[vanilla/Группы интересов/Верующие|Верующие]]
  - `is_interest_group_type` = [[vanilla/Группы интересов/Интеллигенты|Интеллигенты]]
  - `is_interest_group_type` = [[vanilla/Группы интересов/Вооружённые силы|Вооружённые силы]]
  - `is_interest_group_type` = [[vanilla/Группы интересов/Профсоюзы|Профсоюзы]]
- **non_interest_group_leader_trigger**: скрипт, строки 1261–1274
- **interest_group_leader_weight**: скрипт, строки 1276–1281
- **non_interest_group_leader_weight**:
  - `value` = `100`
