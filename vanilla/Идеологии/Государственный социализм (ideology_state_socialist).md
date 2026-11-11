---
type: concept
description: "Идеология «Государственный социализм (ideology_state_socialist)» — ваниль 1.15, `ideology_state_socialist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Государственный социализм (ideology_state_socialist)", "State Socialist", "ideology_state_socialist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_state_socialist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Государственный социализм (ideology_state_socialist)

Идеология · `ideology_state_socialist` · `common/ideologies/01_character_ideologies.txt:3445`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_socialist.dds`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `neutral`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `neutral`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `strongly_disapprove`
- **lawgroup_caste_hegemony**:
  - [[vanilla/Законы/Принудительная кастовая система|Принудительная кастовая система]] = `strongly_disapprove`
  - [[vanilla/Законы/Кодифицированная кастовая система|Кодифицированная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Необязательная кастовая система|Необязательная кастовая система]] = `neutral`
  - [[vanilla/Законы/Позитивная дискриминация|Позитивная дискриминация]] = `approve`
- **lawgroup_edo_social_system**:
  - [[vanilla/Законы/Строгая сословная иерархия|Строгая сословная иерархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Смягчённая сословная иерархия|Смягчённая сословная иерархия]] = `disapprove`
  - [[vanilla/Законы/Гибкая сословная иерархия|Гибкая сословная иерархия]] = `approve`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_approve`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `neutral`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
- **lawgroup_labor_rights**:
  - [[vanilla/Законы/Защита прав рабочих|Защита прав рабочих]] = `strongly_approve`
  - [[vanilla/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[vanilla/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `disapprove`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `strongly_disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `strongly_disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `approve`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Социализм|Социализм]]
- **interest_group_leader_trigger**:
  - `ideology_state_socialist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 3525–3539
- **interest_group_leader_weight**: скрипт, строки 3541–3699
- **non_interest_group_leader_weight**: скрипт, строки 3701–3787
