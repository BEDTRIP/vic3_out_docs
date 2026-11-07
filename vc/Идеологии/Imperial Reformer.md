---
type: concept
description: "Идеология «Imperial Reformer» — VC 1.13, `ideology_imperial_reformer_leader`"
project: vic3
audience: agent
source: vc
aliases: ["Imperial Reformer", "ideology_imperial_reformer_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_imperial_reformer_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# Imperial Reformer

Идеология · `ideology_imperial_reformer_leader` · `common/ideologies/joi_leader_ideologies.txt:737`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_jingoist.dds`
- **character_ideology**: `yes`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `neutral`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `strongly_approve`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `disapprove`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `neutral`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `strongly_approve`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `strongly_disapprove`
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `strongly_disapprove`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `approve`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `strongly_approve`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `strongly_approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `disapprove`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `neutral`
- **lawgroup_labor_rights**:
  - [[vanilla/Законы/Защита прав рабочих|Защита прав рабочих]] = `neutral`
  - [[vanilla/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[vanilla/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `disapprove`
- **country_trigger**: скрипт, строки 789–796
- **interest_group_leader_trigger**:
  - `ideology_utilitarian_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_utilitarian_leader_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 808–832
- **non_interest_group_leader_weight**:
  - `value` = `100`
