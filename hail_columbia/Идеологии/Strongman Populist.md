---
type: concept
description: "Идеология «Strongman Populist» — Hail Columbia 1.13, `ideology_usfp_strongman_populist`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Strongman Populist", "ideology_usfp_strongman_populist"]
tags: [hail_columbia, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_usfp_strongman_populist
paths: [for addon/Hail Columbia/common/ideologies/usfp_leader_ideologies.txt]
---
# Strongman Populist

Идеология · `ideology_usfp_strongman_populist` · `common/ideologies/usfp_leader_ideologies.txt:272`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_usfp_strongman_populist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `strongly_approve`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `approve`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `neutral`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `neutral`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `neutral`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_approve`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `disapprove`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `disapprove`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_approve`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `neutral`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `disapprove`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `disapprove`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `approve`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `neutral`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `approve`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `neutral`
- **lawgroup_policing**:
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `disapprove`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `approve`
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `approve`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_approve`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `disapprove`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `disapprove`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_approve`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `neutral`
  - [[vanilla/Законы/Цензура|Цензура]] = `approve`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_approve`
- **country_trigger**:
  - `usfp_country_is_american` = `yes`
- **interest_group_leader_trigger**: скрипт, строки 352–359
- **non_interest_group_leader_trigger**: скрипт, строки 361–370
- **interest_group_leader_weight**: скрипт, строки 372–395
- **non_interest_group_leader_weight**: скрипт, строки 397–411
