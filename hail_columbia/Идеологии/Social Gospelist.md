---
type: concept
description: "Идеология «Social Gospelist» — Hail Columbia 1.13, `ideology_usfp_social_gospel_leader`"
project: vic3
source: hail_columbia
aliases: ["Social Gospelist", "ideology_usfp_social_gospel_leader"]
tags: [hail_columbia, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_usfp_social_gospel_leader
paths: [for addon/Hail Columbia/common/ideologies/usfp_leader_ideologies.txt]
---
# Social Gospelist

Идеология · `ideology_usfp_social_gospel_leader` · `common/ideologies/usfp_leader_ideologies.txt:164`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_usfp_social_gospel_leader.dds`
- **character_ideology**: `yes`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[hail_columbia/Законы/Свобода совести|Свобода совести]] = `strongly_approve`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `neutral`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `strongly_disapprove`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `strongly_approve`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `approve`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
- **lawgroup_labor_rights**:
  - [[vanilla/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `neutral`
  - [[vanilla/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[vanilla/Законы/Защита прав рабочих|Защита прав рабочих]] = `approve`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `approve`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Подданство|Подданство]] = `disapprove`
  - [[hail_columbia/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `approve`
- **lawgroup_slavery**:
  - [[hail_columbia/Законы/Запрет рабства|Запрет рабства]] = `neutral`
  - [[hail_columbia/Законы/Унаследованное рабство|Унаследованное рабство]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Колониальное рабство|Колониальное рабство]] = `strongly_disapprove`
- **country_trigger**:
  - `usfp_country_is_american` = `yes`
  - `religion` = `rel:protestant`
  - `has_global_variable` = `social_gospel_appeared`
- **interest_group_leader_trigger**:
  - `is_interest_group_type` = [[vanilla/Группы интересов/Верующие|Верующие]]
- **non_interest_group_leader_trigger**: скрипт, строки 229–242
- **interest_group_leader_weight**: скрипт, строки 244–258
- **non_interest_group_leader_weight**: скрипт, строки 260–268
