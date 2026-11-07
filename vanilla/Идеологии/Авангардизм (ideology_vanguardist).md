---
type: concept
description: "Идеология «Авангардизм (ideology_vanguardist)» — ваниль 1.13, `ideology_vanguardist`"
project: vic3
source: vanilla
aliases: ["Авангардизм (ideology_vanguardist)", "Vanguardist", "ideology_vanguardist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_vanguardist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Авангардизм (ideology_vanguardist)

Идеология · `ideology_vanguardist` · `common/ideologies/01_character_ideologies.txt:4010`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_vanguardist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_approve`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_approve`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `neutral`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `approve`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `approve`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `strongly_disapprove`
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Политическая агитация|Политическая агитация]]
- **interest_group_leader_trigger**:
  - `ideology_vanguardist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 4080–4105
- **interest_group_leader_weight**: скрипт, строки 4107–4364
- **non_interest_group_leader_weight**: скрипт, строки 4366–4569
