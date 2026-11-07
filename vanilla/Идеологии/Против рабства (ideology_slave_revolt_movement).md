---
type: concept
description: "Идеология «Против рабства (ideology_slave_revolt_movement)» — ваниль 1.13, `ideology_slave_revolt_movement`"
project: vic3
audience: agent
source: vanilla
aliases: ["Против рабства (ideology_slave_revolt_movement)", "Против рабства", "ideology_slave_revolt_movement"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_slave_revolt_movement
paths: [.vanillaVIC3/common/ideologies/03_ig_ideologies_movement.txt]
---
# Против рабства (ideology_slave_revolt_movement)

Идеология · `ideology_slave_revolt_movement` · `common/ideologies/03_ig_ideologies_movement.txt:1640`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/abolitionist.dds`
- **lawgroup_slavery**:
  - [[vanilla/Законы/Запрет рабства|Запрет рабства]] = `strongly_approve`
  - [[vanilla/Законы/Унаследованное рабство|Унаследованное рабство]] = `disapprove`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `disapprove`
  - [[vanilla/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[vanilla/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `approve`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `approve`
- **lawgroup_policing**:
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `strongly_disapprove`
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `neutral`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `disapprove`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_disapprove`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `approve`
