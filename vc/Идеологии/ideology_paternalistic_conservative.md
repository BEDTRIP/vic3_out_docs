---
type: concept
description: "Идеология «ideology_paternalistic_conservative» — VC 1.13, `ideology_paternalistic_conservative`"
project: vic3
audience: agent
source: vc
aliases: ["ideology_paternalistic_conservative"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_paternalistic_conservative
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# ideology_paternalistic_conservative

Идеология · `ideology_paternalistic_conservative` · `common/ideologies/joi_leader_ideologies.txt:839`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/authoritarian.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `neutral`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `approve`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `neutral`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `neutral`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `approve`
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
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `approve`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `approve`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `disapprove`
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `strongly_disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `neutral`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `approve`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `neutral`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `disapprove`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `neutral`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `approve`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `disapprove`
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `disapprove`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `neutral`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `neutral`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
- **country_trigger**:
  - `country_has_primary_culture` = `cu:north_german`
  - `has_technology_researched` = [[vc/Технологии/Национализм|Национализм]]
- **interest_group_leader_trigger**:
  - `ideology_slaver_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_slaver_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 933–957
- **non_interest_group_leader_weight**:
  - `value` = `100`
