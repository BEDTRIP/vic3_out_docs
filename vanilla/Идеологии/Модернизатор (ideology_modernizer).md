---
type: concept
description: "Идеология «Модернизатор (ideology_modernizer)» — ваниль 1.13, `ideology_modernizer`"
project: vic3
source: vanilla
aliases: ["Модернизатор (ideology_modernizer)", "Modernizer", "ideology_modernizer"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_modernizer
paths: [.vanillaVIC3/common/ideologies/00_ig_ideologies_event.txt]
---
# Модернизатор (ideology_modernizer)

Идеология · `ideology_modernizer` · `common/ideologies/00_ig_ideologies_event.txt:34`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/modernizer.dds`
- **priority**: `100`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `approve`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `neutral`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `disapprove`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `approve`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `neutral`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `neutral`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
