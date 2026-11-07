---
type: concept
description: "Идеология «Суверенизм (ideology_sovereignist_leader)» — ваниль 1.13, `ideology_sovereignist_leader`"
project: vic3
source: vanilla
aliases: ["Суверенизм (ideology_sovereignist_leader)", "Sovereignist", "ideology_sovereignist_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_sovereignist_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Суверенизм (ideology_sovereignist_leader)

Идеология · `ideology_sovereignist_leader` · `common/ideologies/01_character_ideologies.txt:10134`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_sovereignist.dds`
- **character_ideology**: `yes`
- **lawgroup_policing**:
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `approve`
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `neutral`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `disapprove`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_disapprove`
- **lawgroup_migration**:
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `approve`
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `strongly_approve`
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `neutral`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `approve`
- **country_trigger**:
  - `country_is_colonial_or_company` = `yes`
- **interest_group_leader_trigger**:
  - `ideology_sovereignist_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 10176–10183
- **interest_group_leader_weight**: скрипт, строки 10185–10207
- **non_interest_group_leader_weight**: скрипт, строки 10209–10233

## Ссылаются

- **Группы интересов** (character_ideologies): [[vanilla/Группы интересов/Интеллигенты|Интеллигенты]], [[vanilla/Группы интересов/Мелкие буржуа|Мелкие буржуа]]
