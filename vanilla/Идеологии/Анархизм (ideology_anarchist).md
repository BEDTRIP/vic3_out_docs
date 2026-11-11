---
type: concept
description: "Идеология «Анархизм (ideology_anarchist)» — ваниль 1.15, `ideology_anarchist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Анархизм (ideology_anarchist)", "Anarchist", "ideology_anarchist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_anarchist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Анархизм (ideology_anarchist)

Идеология · `ideology_anarchist` · `common/ideologies/01_character_ideologies.txt:5735`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_anarchist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_approve`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `neutral`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `approve`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `strongly_disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_approve`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Военные чиновники|Военные чиновники]] = `strongly_disapprove`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `strongly_disapprove`
  - [[vanilla/Законы/Общественная администрация|Общественная администрация]] = `approve`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_approve`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `disapprove`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `neutral`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_policing**:
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `approve`
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `disapprove`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `disapprove`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Анархизм|Анархизм]]
- **interest_group_leader_trigger**:
  - `ideology_anarchist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 5822–5847
- **interest_group_leader_weight**: скрипт, строки 5849–6107
- **non_interest_group_leader_weight**: скрипт, строки 6109–6293
