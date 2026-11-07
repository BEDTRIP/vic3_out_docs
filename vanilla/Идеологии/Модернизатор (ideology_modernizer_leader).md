---
type: concept
description: "Идеология «Модернизатор (ideology_modernizer_leader)» — ваниль 1.13, `ideology_modernizer_leader`"
project: vic3
source: vanilla
aliases: ["Модернизатор (ideology_modernizer_leader)", "Modernizer", "ideology_modernizer_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_modernizer_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Модернизатор (ideology_modernizer_leader)

Идеология · `ideology_modernizer_leader` · `common/ideologies/01_character_ideologies.txt:10412`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/idealogy_leader_modernizer.dds`
- **character_ideology**: `yes`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `approve`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `neutral`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `neutral`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `neutral`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `approve`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `strongly_approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `neutral`
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `approve`
- **lawgroup_edo_social_system**:
  - [[vanilla/Законы/Строгая сословная иерархия|Строгая сословная иерархия]] = `disapprove`
  - [[vanilla/Законы/Смягчённая сословная иерархия|Смягчённая сословная иерархия]] = `neutral`
  - [[vanilla/Законы/Гибкая сословная иерархия|Гибкая сословная иерархия]] = `approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Академия|Академия]]
- **interest_group_leader_trigger**:
  - `ideology_modernizer_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 10481–10500
- **interest_group_leader_weight**: скрипт, строки 10502–10555
- **non_interest_group_leader_weight**: скрипт, строки 10557–10592
