---
type: concept
description: "Идеология «Reformer» — Mandate of Heaven 1.13, `ideology_moh_reformer`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Reformer", "ideology_moh_reformer"]
tags: [mandate_of_heaven, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_moh_reformer
paths: [for addon/Mandate of Heaven/common/ideologies/moh_leader_ideologies.txt]
---
# Reformer

Идеология · `ideology_moh_reformer` · `common/ideologies/moh_leader_ideologies.txt:1`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_moh_reformer.png`
- **character_ideology**: `yes`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `neutral`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_approve`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `strongly_approve`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `strongly_approve`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `strongly_approve`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `approve`
- **lawgroup_governance_principles**:
  - [[mandate_of_heaven/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `strongly_approve`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `neutral`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `strongly_approve`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
- **country_trigger**: скрипт, строки 48–82
- **interest_group_leader_trigger**:
  - `ideology_moh_reformer_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 88–95
- **non_interest_group_leader_weight**: скрипт, строки 97–115
- **interest_group_leader_weight**: скрипт, строки 117–194

## Ссылаются

- **Группы интересов** (character_ideologies): [[mandate_of_heaven/Группы интересов/Вооружённые силы|Вооружённые силы]], [[mandate_of_heaven/Группы интересов/Интеллигенты|Интеллигенты]], [[mandate_of_heaven/Группы интересов/Мелкие буржуа|Мелкие буржуа]]
