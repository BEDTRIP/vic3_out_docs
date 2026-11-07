---
type: concept
description: "Идеология «Gladstonian Liberal» — VC 1.13, `ideology_gladstonian_liberalism_leader`"
project: vic3
audience: agent
source: vc
aliases: ["Gladstonian Liberal", "ideology_gladstonian_liberalism_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gladstonian_liberalism_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# Gladstonian Liberal

Идеология · `ideology_gladstonian_liberalism_leader` · `common/ideologies/joi_leader_ideologies.txt:401`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_liberal.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `neutral`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `neutral`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_approve`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `neutral`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `disapprove`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `disapprove`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `neutral`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `disapprove`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `disapprove`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `approve`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `neutral`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `neutral`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `disapprove`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `neutral`
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `approve`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `approve`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `neutral`
- **country_trigger**:
  - `has_technology_researched` = [[vc/Технологии/Права человека|Права человека]]
  - `country_has_primary_culture` = `cu:british`
  - `has_variable` = `government_leader_william_gladstone_var`
- **interest_group_leader_trigger**:
  - `ideology_market_liberal_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_market_liberal_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 488–502
- **non_interest_group_leader_weight**:
  - `value` = `250`
