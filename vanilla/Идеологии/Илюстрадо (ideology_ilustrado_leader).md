---
type: concept
description: "Идеология «Илюстрадо (ideology_ilustrado_leader)» — ваниль 1.15, `ideology_ilustrado_leader`"
project: vic3
audience: agent
source: vanilla
aliases: ["Илюстрадо (ideology_ilustrado_leader)", "Ilustrado", "ideology_ilustrado_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_ilustrado_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Илюстрадо (ideology_ilustrado_leader)

Идеология · `ideology_ilustrado_leader` · `common/ideologies/01_character_ideologies.txt:12721`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_ilustrado.dds`
- **character_ideology**: `yes`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `disapprove`
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Подданство|Подданство]] = `neutral`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `neutral`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `strongly_approve`
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `neutral`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `neutral`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
- **country_trigger**: пусто
- **interest_group_leader_trigger**:
  - `ideology_ilustrado_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 12764–12777
- **interest_group_leader_weight**: скрипт, строки 12779–12799
- **non_interest_group_leader_weight**: скрипт, строки 12801–12821
