---
type: concept
description: "Идеология «Бакухан (ideology_japan_hierarchic)» — ваниль 1.13, `ideology_japan_hierarchic`"
project: vic3
audience: agent
source: vanilla
aliases: ["Бакухан (ideology_japan_hierarchic)", "Bakuhan", "ideology_japan_hierarchic"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_japan_hierarchic
paths: [.vanillaVIC3/common/ideologies/00_ig_ideologies_flavored.txt]
---
# Бакухан (ideology_japan_hierarchic)

Идеология · `ideology_japan_hierarchic` · `common/ideologies/00_ig_ideologies_flavored.txt:1568`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/hierarchic.dds`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `neutral`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_approve`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `approve`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `strongly_disapprove`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `approve`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `approve`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `disapprove`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `approve`
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `disapprove`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `neutral`
  - [[vanilla/Законы/Подданство|Подданство]] = `approve`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `neutral`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `approve`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `neutral`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `disapprove`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_disapprove`
- **lawgroup_edo_social_system**:
  - [[vanilla/Законы/Строгая сословная иерархия|Строгая сословная иерархия]] = `strongly_approve`
  - [[vanilla/Законы/Смягчённая сословная иерархия|Смягчённая сословная иерархия]] = `approve`
  - [[vanilla/Законы/Гибкая сословная иерархия|Гибкая сословная иерархия]] = `disapprove`
