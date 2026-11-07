---
type: concept
description: "Идеология «One-Nation Conservative» — VC 1.13, `ideology_one_nation_conservatism_leader`"
project: vic3
audience: agent
source: vc
aliases: ["One-Nation Conservative", "ideology_one_nation_conservatism_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_one_nation_conservatism_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# One-Nation Conservative

Идеология · `ideology_one_nation_conservatism_leader` · `common/ideologies/joi_leader_ideologies.txt:626`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_sovereignist.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `neutral`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `strongly_approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `disapprove`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `approve`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `strongly_disapprove`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `neutral`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `neutral`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `disapprove`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `neutral`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `approve`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `disapprove`
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `disapprove`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `neutral`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `approve`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
- **country_trigger**: скрипт, строки 696–704
- **interest_group_leader_trigger**:
  - `ideology_utilitarian_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_utilitarian_leader_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 716–730
- **non_interest_group_leader_weight**:
  - `value` = `250`
