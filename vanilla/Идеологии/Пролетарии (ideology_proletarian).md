---
type: concept
description: "Идеология «Пролетарии (ideology_proletarian)» — ваниль 1.13, `ideology_proletarian`"
project: vic3
audience: agent
source: vanilla
aliases: ["Пролетарии (ideology_proletarian)", "Proletarian", "ideology_proletarian"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_proletarian
paths: [.vanillaVIC3/common/ideologies/00_ig_ideologies.txt]
---
# Пролетарии (ideology_proletarian)

Идеология · `ideology_proletarian` · `common/ideologies/00_ig_ideologies.txt:667`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/proletarian.dds`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `disapprove`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `neutral`
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `neutral`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `approve`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_approve`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `neutral`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_approve`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `strongly_disapprove`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `disapprove`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `disapprove`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `neutral`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `strongly_disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `disapprove`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `approve`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_approve`

## Ссылаются

- **Группы интересов** (идеология группы): [[vanilla/Группы интересов/Профсоюзы|Профсоюзы]]
