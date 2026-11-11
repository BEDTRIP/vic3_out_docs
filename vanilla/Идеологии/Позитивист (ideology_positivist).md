---
type: concept
description: "Идеология «Позитивист (ideology_positivist)» — ваниль 1.15, `ideology_positivist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Позитивист (ideology_positivist)", "Positivist", "ideology_positivist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_positivist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Позитивист (ideology_positivist)

Идеология · `ideology_positivist` · `common/ideologies/01_character_ideologies.txt:8582`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_positivist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `neutral`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `neutral`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `approve`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_approve`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `strongly_approve`
  - [[vanilla/Законы/Военные чиновники|Военные чиновники]] = `approve`
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `strongly_disapprove`
  - [[vanilla/Законы/Общественная администрация|Общественная администрация]] = `strongly_disapprove`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Эмпиризм|Эмпиризм]]
  - `has_global_variable` = `positivism_invented`
- **interest_group_leader_trigger**:
  - `ideology_positivist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 8634–8658
- **interest_group_leader_weight**: скрипт, строки 8660–8813
- **non_interest_group_leader_weight**: скрипт, строки 8815–8924
