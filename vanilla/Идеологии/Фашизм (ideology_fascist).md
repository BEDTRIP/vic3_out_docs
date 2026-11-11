---
type: concept
description: "Идеология «Фашизм (ideology_fascist)» — ваниль 1.15, `ideology_fascist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Фашизм (ideology_fascist)", "Fascist", "ideology_fascist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_fascist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Фашизм (ideology_fascist)

Идеология · `ideology_fascist` · `common/ideologies/01_character_ideologies.txt:5181`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_fascist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `neutral`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `neutral`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `strongly_approve`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `approve`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `approve`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `neutral`
  - [[vanilla/Законы/Технократия|Технократия]] = `neutral`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_approve`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `approve`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `approve`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `disapprove`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `strongly_disapprove`
  - [[vanilla/Законы/Революционная гвардия|Революционная гвардия]] = `strongly_disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `strongly_disapprove`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `neutral`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_approve`
  - [[vanilla/Законы/Чрезвычайная комиссия|Чрезвычайная комиссия]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `disapprove`
  - [[vanilla/Законы/Цензура|Цензура]] = `neutral`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `approve`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `approve`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_approve`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 5250–5255
- **interest_group_leader_trigger**:
  - `ideology_fascist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 5261–5275
- **interest_group_leader_weight**: скрипт, строки 5277–5520
- **non_interest_group_leader_weight**: скрипт, строки 5522–5732
