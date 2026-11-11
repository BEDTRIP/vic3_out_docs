---
type: concept
description: "Идеология «Polkist Expansionist» — VC 1.15, `ideology_polk_jingoist_leader`"
project: vic3
audience: agent
source: vc
aliases: ["Polkist Expansionist", "ideology_polk_jingoist_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_polk_jingoist_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# Polkist Expansionist

Идеология · `ideology_polk_jingoist_leader` · `common/ideologies/joi_leader_ideologies.txt:965`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/jackson_democrat.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
- **lawgroup_slavery**:
  - [[vanilla/Законы/Запрет рабства|Запрет рабства]] = `strongly_disapprove`
  - [[vanilla/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[vanilla/Законы/Работорговля|Работорговля]] = `neutral`
  - [[vanilla/Законы/Унаследованное рабство|Унаследованное рабство]] = `approve`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `approve`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_approve`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `disapprove`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `neutral`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `approve`
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `approve`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `strongly_approve`
- **country_trigger**: скрипт, строки 1021–1027
- **interest_group_leader_trigger**:
  - `ideology_integralist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**:
  - **interest_group**:
    - `ideology_integralist_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 1039–1044
- **non_interest_group_leader_weight**:
  - `value` = `100`
