---
type: concept
description: "Идеология «Суверенизм (ideology_sovereignist)» — ваниль 1.13, `ideology_sovereignist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Суверенизм (ideology_sovereignist)", "Sovereignist", "ideology_sovereignist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_sovereignist
paths: [.vanillaVIC3/common/ideologies/00_ig_ideologies_flavored.txt]
---
# Суверенизм (ideology_sovereignist)

Идеология · `ideology_sovereignist` · `common/ideologies/00_ig_ideologies_flavored.txt:796`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/sovereignist.dds`
- **lawgroup_policing**:
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `approve`
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `neutral`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `disapprove`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_disapprove`
- **lawgroup_migration**:
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `approve`
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `strongly_approve`
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Подданство|Подданство]] = `neutral`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `approve`
