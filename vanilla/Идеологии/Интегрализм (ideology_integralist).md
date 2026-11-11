---
type: concept
description: "Идеология «Интегрализм (ideology_integralist)» — ваниль 1.15, `ideology_integralist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Интегрализм (ideology_integralist)", "Integralist", "ideology_integralist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_integralist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Интегрализм (ideology_integralist)

Идеология · `ideology_integralist` · `common/ideologies/01_character_ideologies.txt:9205`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_integralist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Теократия|Теократия]] = `approve`
  - [[vanilla/Законы/Монархия|Монархия]] = `approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `neutral`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_approve`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `approve`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `neutral`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `disapprove`
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `approve`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `strongly_disapprove`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `neutral`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_approve`
  - [[vanilla/Законы/Чрезвычайная комиссия|Чрезвычайная комиссия]] = `strongly_disapprove`
- **lawgroup_policing**:
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_approve`
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `approve`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `approve`
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `approve`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `approve`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_approve`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 9273–9282
- **interest_group_leader_trigger**:
  - `ideology_integralist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 9288–9302
- **interest_group_leader_weight**: скрипт, строки 9304–9546
- **non_interest_group_leader_weight**: скрипт, строки 9548–9736
