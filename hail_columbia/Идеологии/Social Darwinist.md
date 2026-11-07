---
type: concept
description: "Идеология «Social Darwinist» — Hail Columbia 1.13, `ideology_usfp_social_darwinist_leader`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Social Darwinist", "ideology_usfp_social_darwinist_leader"]
tags: [hail_columbia, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_usfp_social_darwinist_leader
paths: [for addon/Hail Columbia/common/ideologies/usfp_leader_ideologies.txt]
---
# Social Darwinist

Идеология · `ideology_usfp_social_darwinist_leader` · `common/ideologies/usfp_leader_ideologies.txt:836`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/unused/ideology_leader_individualist.dds`
- **character_ideology**: `yes`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `disapprove`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `neutral`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `neutral`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_approve`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `neutral`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `neutral`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `neutral`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `disapprove`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `strongly_disapprove`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_approve`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Протекционизм|Протекционизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `disapprove`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `neutral`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `strongly_disapprove`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_disapprove`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `strongly_approve`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `approve`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `neutral`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `disapprove`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `disapprove`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `neutral`
- **lawgroup_migration**:
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `disapprove`
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `approve`
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `neutral`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Подданство|Подданство]] = `disapprove`
  - [[hail_columbia/Законы/Этническое государство|Этническое государство]] = `strongly_approve`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `approve`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `disapprove`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_disapprove`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `strongly_disapprove`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `approve`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `strongly_approve`
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `neutral`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `approve`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 919–934
- **interest_group_leader_trigger**: скрипт, строки 936–944
- **non_interest_group_leader_trigger**: скрипт, строки 946–956
- **interest_group_leader_weight**: скрипт, строки 958–1001
- **non_interest_group_leader_weight**: скрипт, строки 1003–1028
