---
type: concept
description: "Идеология «Либерализм (ideology_liberal_movement)» — ваниль 1.13, `ideology_liberal_movement`"
project: vic3
audience: agent
source: vanilla
aliases: ["Либерализм (ideology_liberal_movement)", "Liberal", "ideology_liberal_movement"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_liberal_movement
paths: [.vanillaVIC3/common/ideologies/03_ig_ideologies_movement.txt]
---
# Либерализм (ideology_liberal_movement)

Идеология · `ideology_liberal_movement` · `common/ideologies/03_ig_ideologies_movement.txt:532`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/liberal.dds`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `approve`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `disapprove`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `neutral`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `approve`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `approve`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `approve`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `neutral`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `approve`
