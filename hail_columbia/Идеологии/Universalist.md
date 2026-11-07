---
type: concept
description: "Идеология «Universalist» — Hail Columbia 1.13, `ideology_usfp_universalist`"
project: vic3
source: hail_columbia
aliases: ["Universalist", "ideology_usfp_universalist"]
tags: [hail_columbia, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_usfp_universalist
paths: [for addon/Hail Columbia/common/ideologies/usfp_leader_ideologies.txt]
---
# Universalist

Идеология · `ideology_usfp_universalist` · `common/ideologies/usfp_leader_ideologies.txt:1032`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_usfp_universalist.dds`
- **character_ideology**: `yes`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `approve`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `strongly_disapprove`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `strongly_disapprove`
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `disapprove`
  - [[hail_columbia/Законы/Свобода совести|Свобода совести]] = `neutral`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_approve`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Подданство|Подданство]] = `disapprove`
  - [[hail_columbia/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_approve`
- **lawgroup_caste_hegemony**:
  - [[vanilla/Законы/Принудительная кастовая система|Принудительная кастовая система]] = `strongly_disapprove`
  - [[vanilla/Законы/Кодифицированная кастовая система|Кодифицированная кастовая система]] = `strongly_disapprove`
  - [[vanilla/Законы/Необязательная кастовая система|Необязательная кастовая система]] = `neutral`
  - [[vanilla/Законы/Позитивная дискриминация|Позитивная дискриминация]] = `strongly_approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Права человека|Права человека]]
- **interest_group_leader_trigger**:
  - `is_interest_group_type` = [[vanilla/Группы интересов/Верующие|Верующие]]
- **non_interest_group_leader_trigger**: скрипт, строки 1082–1094
- **interest_group_leader_weight**: скрипт, строки 1097–1140
- **non_interest_group_leader_weight**: скрипт, строки 1142–1185
