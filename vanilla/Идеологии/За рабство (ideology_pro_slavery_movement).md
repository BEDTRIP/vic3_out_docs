---
type: concept
description: "Идеология «За рабство (ideology_pro_slavery_movement)» — ваниль 1.15, `ideology_pro_slavery_movement`"
project: vic3
audience: agent
source: vanilla
aliases: ["За рабство (ideology_pro_slavery_movement)", "За рабство", "ideology_pro_slavery_movement"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_pro_slavery_movement
paths: [.vanillaVIC3/common/ideologies/03_ig_ideologies_movement.txt]
---
# За рабство (ideology_pro_slavery_movement)

Идеология · `ideology_pro_slavery_movement` · `common/ideologies/03_ig_ideologies_movement.txt:21`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/slaver.dds`
- **lawgroup_policing**:
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `approve`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `disapprove`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `neutral`
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `strongly_disapprove`
- **lawgroup_slavery**:
  - [[vanilla/Законы/Работорговля|Работорговля]] = `approve`
  - [[vanilla/Законы/Долговое рабство|Долговое рабство]] = `approve`
  - [[vanilla/Законы/Унаследованное рабство|Унаследованное рабство]] = `approve`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `disapprove`
  - [[vanilla/Законы/Запрет рабства|Запрет рабства]] = `strongly_disapprove`
